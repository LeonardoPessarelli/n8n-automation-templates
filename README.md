# n8n Automation Templates

Coleção de workflows n8n para agentes de IA conversacionais de vendas e atendimento. Desenvolvidos e operados em produção.

## Estrutura

| Pasta | Descrição |
|---|---|
| [`elisa-sales-agent/`](elisa-sales-agent/) | Agente de vendas completo — WhatsApp, Instagram, follow-up, pedidos e pagamentos |
| [`elisa-mcp/`](elisa-mcp/) | MCP Servers e Tools para comunicação entre agentes |
| [`sdr-voice-agent/`](sdr-voice-agent/) | Agente de voz SDR para prospecção automatizada via Vapi |
| [`restaurant-agent/`](restaurant-agent/) | Agente de atendimento para restaurante |
| [`utilities/`](utilities/) | Reativação de leads, lembretes, alertas e integrações auxiliares |

## Stack

- **n8n** — orquestração de workflows
- **Claude AI** — modelo de linguagem dos agentes
- **Evolution API** — integração WhatsApp
- **Supabase** — banco de dados e memória dos agentes
- **Redis** — buffer de mensagens e controle de estado
- **Asaas** — integração de pagamentos (Pix e cartão)
- **Vapi** — agente de voz

## Como usar

1. Importe o arquivo `.json` desejado no seu n8n
2. Configure as credenciais nos nós marcados com `YOUR_*`
3. Ative o workflow

> As credenciais reais foram removidas. Substitua os placeholders `YOUR_EVOLUTION_API_HOST`, `YOUR_N8N_HOST` e `YOUR_SUPABASE_HOST` pelos seus valores.

## Resultado documentado

Venda de **R$ 286,29** fechada em **43 minutos** sem intervenção humana — smartwatch + upsell fone + frete calculado automaticamente.
