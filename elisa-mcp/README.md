# Elisa — MCP Servers e Tools

MCP (Model Context Protocol) Servers que expõem ferramentas para o agente Claude AI consultar dados e executar ações durante a conversa.

## Workflows

| Arquivo | Função |
|---|---|
| `MCP-Server-whats.json` | Servidor MCP principal — expõe tools via WhatsApp |
| `Tools-MCPwhats.json` | Tools do agente: consulta catálogo, calcula frete, registra pedido |
| `MCP-SERVER-Telegram.json` | Servidor MCP via Telegram |
| `Tools-MCP-Telegram.json` | Tools para o agente no canal Telegram |

## Como funciona

O agente Claude AI chama as tools durante a conversa para buscar informações em tempo real no Supabase (produtos, estoque, preços) e executar ações (criar pedido, calcular frete).
