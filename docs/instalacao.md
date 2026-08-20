# Instalação detalhada

INCRA SIGEF: Detalhes de Parcela é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_incra_sigef_detalhes_parcela`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_incra_sigef_detalhes_parcela` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_incra_sigef_detalhes_parcela` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_incra_sigef_detalhes_parcela` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.incra_sigef_detalhes_parcela` (ou `servers.incra_sigef_detalhes_parcela` no VS Code) do config do cliente e reinicie.
