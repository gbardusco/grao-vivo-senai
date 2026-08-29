---
aliases: ["Gatilhos Grão Vivo - Índice", "Gatilhos por Persona Atv2"]
tags: [senai, gatilhos, atividade2, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_2_Aluno_Neuromarketing_e_Calendario_de_Conteudo.docx
tipo: entregavel
---

# Gatilhos — Grão Vivo (Atividade 2 — Entregável a)

> [!QUOTE] Fonte — `Atividade_2_Aluno_Neuromarketing_e_Calendario_de_Conteudo.docx:31,39` + `TABLE 3`
> `b) selecionar, para cada uma das 2 personas da Atividade 1, no mínimo 3 gatilhos mentais distintos (escassez, urgência, prova social, reciprocidade, ancoragem, identidade/pertencimento ou dopamina), associando-os às etapas do funil (topo, meio e fundo);` — `Atividade_2_...docx:31`
> `a) gatilhos mentais atribuídos a cada persona e etapa do funil;` — `Atividade_2_...docx:39`

> [!INFO] Personas base Atv1
> `[[../personas/persona-01-indecisa-curadoria|Ana Clara 34 — Indecisa Curadoria]]` — `“não sei qual café combina comigo”` + SLA
> `[[../personas/persona-02-comparador-valor|Rafael Moura 38 — Comparador Valor]]` — `“vale a pena R$45?” + “não vi ninguém comentando”` — ver `docs/09-tarefas-gatilhos-funil.md`

## Arquivos

| # | Arquivo | Persona | Gatilhos (≥3) |
|---|---|---|---|
| 01 | [[gatilhos-ana-clara\|gatilhos-ana-clara.md]] | Ana Clara 34 — curadoria | Dopamina (topo) → Reciprocidade (meio) → Escassez+Identidade (fundo) |
| 02 | [[gatilhos-rafael-moura\|gatilhos-rafael-moura.md]] | Rafael Moura 38 — valor/prova | Prova social (topo) → Ancoragem (meio) → Urgência+Identidade (fundo) |
| 03 | [[gatilhos-matriz-geral\|gatilhos-matriz-geral.md]] | Ambas — matriz comparativa | Consolida + S1/S2 + canal + métrica para entrega |

> [!IMPORTANT] Critérios Críticos Atv2 — `TABLE 3`
> - CC-a: S1 (emo) vs S2 (rac) correto — Ancoragem S2→S1, demais S1
> - CC-b: ≥3 distintos por persona no funil

## Dataview

```dataview
TABLE persona, dificuldade
FROM "docs/entregaveis/gatilhos"
WHERE tipo = "entregavel"
SORT file.name ASC
```

#gatilhos #atividade2
