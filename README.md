# AI Code Assistants - MCP Support

WIP!! Please send PRs.

| Code Assistant  | STDIO | SSE | Streamable HTTP | Tools | Tools Updated | Resources | Prompts | Roots | Sampling |
|-----------------|:-----:|:---:|:---------------:|:-----:|:-------------:|:---------:|:-------:|:-----:|:--------:|
| Amazon Q CLI    |  👍   | 🚫  |       🚫        |  👍   |      🚫       |    🚫     |   👍    |  🚫   |    🚫    |
| Amazon Q in IDE |  🚫   | 🚫  |       🚫        |  🚫   |      🚫       |    🚫     |   🚫    |  🚫   |    🚫    |
| Claude Code     |  👍   | 👍  |       👍        |  👍   |       ❓       |    🚫     |   👍    |   ❓   |    ❓     |
| Claude Desktop  |  👍   |  ❓  |       👍        |  👍   |       ❓       |    👍     |    ❓    |   ❓   |    ❓     |
| Cline           |  👍   | 👍  |        ❓        |  👍   |       ❓       |    👍     |    ❓    |   ❓   |    ❓     |
| Copilot         |  👍   |  ❓  |        ❓        |  👍   |       ❓       |     ❓     |    ❓    |  👍   |    ❓     |
| Cursor          |  👍   |  ❓  |        ❓        |  👍   |       ❓       |     ❓     |    ❓    |   ❓   |    ❓     |
| DevoxxGenie     |  👍   | 👍  |       👍        |  👍   |      👍       |    👍     |   👍    |  🚫   |    👍    |
| Windsurf        |  👍   |  ❓  |        ❓        |  👍   |       ❓       |     ❓     |    ❓    |   ❓   |    ❓     |
| Zed             |  👍   |  ❓  |        ❓        |  👍   |       ❓       |     ❓     |   👍    |   ❓   |    ❓     |

# Legend
Explanation of columns:

| Column          | Meaning                                                                                                   |
|-----------------|-----------------------------------------------------------------------------------------------------------|
| STDIO           | Indicates whether the assistant supports interaction via standard input/output (command-line interface).  |
| SSE             | Indicates support for Server-Sent Events, a protocol for streaming updates from server to client.         |
| Streamable HTTP | Whether the tool supports streaming responses over HTTP (e.g., live code suggestions as you type).        |
| Tools           | Shows if the assistant provides access to additional tools (e.g., code search, refactoring, debugging).   |
| Tools Updated   | Indicates if the tools or their underlying models are regularly updated or refreshed.                     |
| Resources       | Whether the assistant can access or manage external resources (files, APIs, databases, etc.).             |
| Prompts         | Indicates support for prompt engineering or custom prompts (user-defined instructions/templates).         |
| Roots           | Indicates support for multi-root workspaces or projects (handling multiple codebases at once).            |
| Sampling        | Indicates if the assistant allows sampling (e.g., controlling randomness/temperature in code generation). |

Explanation of rating:
* 👍 = Supported/Available
* 🚫 = Not supported/Unavailable
* ❓ = Unknown or unclear from available documentation