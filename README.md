# ssoft-ai marketplace

Plugins and skills for AI agents from the [ssoft-ai](https://github.com/ssoft-ai) projects,
listed in one place. The listing takes the Claude Code marketplace format; another agent takes a
plugin's skills from the plugin's own repository.

## Plugins

| Plugin | What it gives | Repository |
|---|---|---|
| `sdlc` | software development life cycle skills after the industry standards, from the life cycle as a whole down to languages and tools | [ssoft-ai/sdlc](https://github.com/ssoft-ai/sdlc) |

## Installation in Claude Code

Add the marketplace once:

```sh
claude plugin marketplace add ssoft-ai/marketplace
```

Then install a plugin from it:

| Plugin | Command |
|---|---|
| `sdlc` | `claude plugin install sdlc@ssoft-ai` |

A plugin is installed from the default branch of its repository.

| Action | Command |
|---|---|
| refresh the list of plugins | `claude plugin marketplace update ssoft-ai` |
| update a plugin | `claude plugin update <plugin>` |
| remove a plugin | `claude plugin uninstall <plugin>` |

## Licence

[MIT](LICENSE.md).
