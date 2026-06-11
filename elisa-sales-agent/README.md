# Elisa — Agente de Vendas com IA

Agente conversacional completo para vendas via WhatsApp e Instagram. Atende, qualifica, envia mídia, calcula frete e fecha pedidos com pagamento integrado — sem intervenção humana.

## Resultado documentado

Venda de **R$ 286,29** fechada em **43 minutos**: smartwatch + upsell fone + frete calculado automaticamente via CEP.

## Workflows

| Arquivo | Função |
|---|---|
| `Whatsapp.json` | Workflow principal — recebe mensagens, aciona o agente Claude AI, envia respostas em texto e áudio |
| `Instagram.json` | Atendimento via Instagram DM com o mesmo agente |
| `Follow-Up.json` | Recontata leads que não finalizaram a conversa |
| `Desativar-agente.json` | Desativa o agente para atendimento humano manual |
| `Verificação-de-Pagamento.json` | Confirma pagamento recebido via webhook Asaas |
| `Pedido.json` | Cria cobrança Pix/cartão via Asaas e registra o pedido |
| `Alerta-de-Erro.json` | Notifica erros críticos via Telegram |

## Integrações

- Evolution API (WhatsApp)
- Claude AI (agente conversacional)
- Supabase (catálogo de produtos, histórico de clientes)
- Redis (buffer de mensagens)
- Asaas (pagamentos)
- Melhor Envio (cálculo de frete)
