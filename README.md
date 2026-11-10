# DemoMCP

A basic introduction to MCP (Model Context Protocol) in .NET: a simple stdio server exposing weather tools (`get_forecast`, `get_alerts`).

## Using the server

| Client                                                    | Configuration                                                                                      |
| --------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| Claude Code (terminal and the Code tab of Claude Desktop) | `.mcp.json` (included in this repository)                                                          |
| GitHub Copilot (Visual Studio)                            | `.mcp.json` in the solution root (same file)                                                       |
| Claude Desktop (chat)                                     | Copy `claude_desktop_config.example.json` to your `claude_desktop_config.json` and adjust the path |

Adjust the project path inside the config files to match your machine.

> Note: `.mcp.json` is only read when a session starts. Restart the session after editing it.
