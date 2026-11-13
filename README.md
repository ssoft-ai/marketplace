# ssoft-ai marketplace

Plugins and skills for AI agents from the [ssoft-ai](https://github.com/ssoft-ai) projects,
listed in one place. The listing takes the Claude Code marketplace format; another agent takes a
plugin's skills from the plugin's own repository.

## Plugins

| Plugin | What it gives | Repository |
|---|---|---|
| `sdlc` | software development life cycle skills after the industry standards, from the life cycle as a whole down to languages and tools | [ssoft-ai/sdlc](https://github.com/ssoft-ai/sdlc) |
| `skill-router` | a search over every installed skill source for the skills a request needs, including skills the session's skill list does not show | [ssoft-ai/skill-router](https://github.com/ssoft-ai/skill-router) |

## Installation in Claude Code

Add the marketplace once:

```sh
claude plugin marketplace add ssoft-ai/marketplace
```

Then install a plugin from it:

| Plugin | Command |
|---|---|
| `sdlc` | `claude plugin install sdlc@ssoft-ai` |
| `skill-router` | `claude plugin install skill-router@ssoft-ai` |

| Plugin | Installed from |
|---|---|
| `sdlc` | the default branch of its repository |
| `skill-router` | its latest release tag |

| Action | Command |
|---|---|
| refresh the list of plugins | `claude plugin marketplace update ssoft-ai` |
| update a plugin | `claude plugin update <plugin>` |
| remove a plugin | `claude plugin uninstall <plugin>` |

## Licence

[MIT](LICENSE.md).
