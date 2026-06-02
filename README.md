# ⚖️ Dashboard Jurídico · Lucralize

Dashboard de acompanhamento comercial do **Funil de BPO Jurídico**, integrado ao Agendor via proxy Railway.

🔗 **Acesso:** [lucralize-comercial.github.io/dashboard-juridico/dashboard_juridico.html](https://lucralize-comercial.github.io/dashboard-juridico/dashboard_juridico.html)

---

## 📊 Funcionalidades

- **Visão Geral** — métricas do período, evolução mensal, pipeline por etapa, responsáveis, últimos negócios e motivos de perda
- **Análise de Conversão** — desempenho por origem, gráficos de volume e conversão
- **Acompanhamento** — leads parados, pipeline por responsável, etapas críticas
- **Contratos Ganhos** — histórico de negócios fechados com filtros por responsável e busca

## ⚙️ Configuração

| Item | Valor |
|------|-------|
| Fonte de dados | Agendor API v3 |
| Proxy | `agendo-proxy-production.up.railway.app` |
| Funil | Funil de BPO Jurídico |
| Atualização automática | A cada 1 hora |

## 🔄 Como atualizar os dados

1. Acesse o dashboard pelo link acima
2. Clique em **Atualizar base** no canto superior direito
3. Aguarde a confirmação e clique novamente após 5 minutos para carregar os dados frescos

## 📁 Estrutura

```
dashboard-juridico/
└── dashboard_juridico.html   # Arquivo principal do dashboard
```
