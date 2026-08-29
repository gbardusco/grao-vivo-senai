---
aliases: ["KPIs e Medição", "Indicadores Grão Vivo"]
tags: [senai, kpis, medicao, ct3, ct6, atividade3, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_3_Aluno_Producao_dos_Criativos_e_Medicao_de_Resultados.docx
prev: "[[15-tarefas-criativos|15 — Tarefas Criativos]]"
next: "[[17-etica-ia|17 — Ética]]"
---

# 16 — Tarefas d: KPIs e Medição

> [!QUOTE] Fonte — `Atividade_3_Aluno_Producao_dos_Criativos_e_Medicao_de_Resultados.docx:33,37`
> `d) perguntar a uma Inteligência Artificial generativa quais indicadores-chave de desempenho (KPIs) são adequados para avaliar uma campanha de lançamento de produto em e-commerce e, a partir da resposta obtida, selecionar e justificar no mínimo 4 (quatro) KPIs para a campanha da Grão Vivo, especificando definição, forma de mensuração e meta;` — `Atividade_3_...docx:33`
> `Utilizar IA para: (iii) pesquisar quais KPIs são adequados a uma campanha de lançamento em e-commerce, registrando o prompt e a resposta obtida antes de selecionar os indicadores utilizados.` — `Atividade_3_...docx:37`

> [!IMPORTANT] Crítico c — `TABLE 3` Atv3
> `c) lista no mínimo 4 KPIs coerentes com a campanha, com definição, forma de mensuração e evidência da consulta à IA que fundamentou a escolha;`

## Prompt modelo — perguntar à IA

> [!EXAMPLE] Copiar e colar

````markdown
# CONTEXTO — Grão Vivo (Atv3)
- Campanha lançamento torra média premium, meta +20% vendas digitais 1º mês, canais IG 8.200 / WhatsApp / feira, calendário 3 posts (Topo Reels Dopamina, Meio Carrossel Reciprocidade/Ancoragem, Fundo WhatsApp Escassez) — ver docs/entregaveis/calendario/calendario-geral-3-posts.md
- Peças já com gatilhos S1/S2

# PERGUNTA À IA
Quais KPIs são adequados para avaliar campanha de lançamento de produto em e-commerce? Liste 8-10 com definição.

# TAREFA PÓS-RESPOSTA
A partir da resposta, selecionei 4 KPIs coerentes com Grão Vivo (topo/meio/fundo) e justifico definição, mensuração e meta.
````

> [!TIP] Registre prompt + resposta em `[[templates/kpis-4-indicadores|kpis-4-indicadores.md]]` + `docs/entregaveis/registro-prompts.md`

## Tabela — 4+ KPIs para Grão Vivo (exemplo entrega)

| # | KPI | Definição | Forma de mensuração | Meta campanha +20% | Ligado a | Gatilho/peça |
|---|---|---|---|---|---|---|
| 1 | **CTR Quiz / CTR Reels** | `Cliques no quiz / views Reels` | IG Insights `CTR Reels Topo` | `>12% CTR quiz` | Topo Post 01 Dopamina | Reels quiz |
| 2 | **Taxa de Conversão Fundo** | `Vendas / visitantes loja` | Loja virtual (Shopify/VTEX) `conversão fundo` | `>4%` (vs ~2% atual) | Fundo Post 03 Escassez | WhatsApp/feira |
| 3 | **Tempo Resposta WhatsApp** | `Tempo médio 1ª resposta` | WhatsApp Business API logs | `<2 min` | Consideração Post 02 | Chatbot NLP |
| 4 | **Ticket médio** | `Receita / nº pedidos` | Loja `R$45` | `Manter R$45 + kit 3×50g` | Fundo | Kit |
| 5 | _(bônus)_ **Taxa Retirada Feira** | `Pedidos retira feira / total` | Feira sábado check | `>30% pedidos fundo` | Fundo Post 03 | Feira |
| 6 | _(bônus)_ **Crescimento Vendas Digitais** | `(Vendas mês - base)/base` | Loja comparativo mensal | `+20%` | Geral | Meta Quadro 2 |

> [!WARNING] Pelo menos 4 são obrigatórios — escolha 4 que cubram topo→fundo + meta. Incluir prompt+resposta é crítico.

## Conexão com Capacidades

- **CT3** `publicidade programática` — entender mídia paga se usar Reels pago — KPIs de mídia (CTR, CPM)
- **CT6** `coleta e análise dados` — KPIs + mensuração + meta — evidência prompt IA

- [ ] Perguntei à IA e salvei prompt+resposta #tarefa/d-atv3
- [ ] Selecionei ≥4 KPIs com definição+mensuração+meta #criterio/critico

---
> [!SUCCESS] Próximo
> [[17-etica-ia|17 — Ética]] + [[18-reflexao-final|Reflexão]].

#kpis #medicao
