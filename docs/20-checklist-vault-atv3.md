---
aliases: ["Checklist Atv3", "Revisão Final Atv3"]
tags: [senai, checklist, atividade3, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_3_Aluno_Producao_dos_Criativos_e_Medicao_de_Resultados.docx
prev: "[[19-entregavel-avaliacao-atv3|19 — Entregável Atv3]]"
next: "[[README|README]]"
---

# 20 — Checklist Final e Vault — Atividade 3

> [!QUOTE] Fonte consolidada — `Atividade_3_Aluno_Producao_dos_Criativos_e_Medicao_de_Resultados.docx:40-45` + `TABLE 3`

## Checklist Críticos Atv3

- [ ] 3 peças prontas com gatilho+canal Atv2 + ≥1 sensorial digital — `[[15-tarefas-criativos]]` #criterio/critico
- [ ] Cada peça com ≥1 alteração + justificativa (revisão crítica) #criterio/critico
- [ ] Conceito visual cada peça (composição, cores creme/café, sensorial) #criterio/critico
- [ ] ≥4 KPIs com definição+mensuração+meta + prompt+resposta IA — `[[16-kpis-medicao]]` #criterio/critico
- [ ] Nota ética IA (transparência, direitos autorais Pexels, verificação humana) — `[[17-etica-ia]]` #criterio/critico
- [ ] Reflexão ≥10 linhas ligando IA às etapas Atv1→Atv3 — `[[18-reflexao-final]]` #criterio/critico
- [ ] Reaproveitou `[[../entregaveis/personas/persona-01-indecisa-curadoria|Ana]]`, `[[../entregaveis/personas/persona-02-comparador-valor|Rafael]]`, `[[../entregaveis/gatilhos/gatilhos-matriz-geral|gatilhos]]`, `[[../entregaveis/calendario/calendario-geral-3-posts|calendário]]` #reaproveitamento

## Desejáveis

- [ ] Ajustes KPI condicionados (ex: conversão fundo <4% → reforçar escassez) #desejavel
- [ ] Visão sistêmica personas→gatilhos→calendário→criativos→KPIs #desejavel
- [ ] Ferramenta automação (Meta Business Suite, mLabs, RD Station) #desejavel

## Entregáveis Atv3 — Pastas

| Entregável | Pasta | Arquivo exemplo |
|---|---|---|
| a) 3 peças | `docs/entregaveis/criativos/` | `peca-01-topo-dopamina.md` |
| b) Conceito visual | `criativos/` | `conceito-visual-01.md` ou na mesma peça |
| c) KPIs | `docs/entregaveis/kpis/` | `kpis-4-indicadores.md` + `prompt-kpis.md` |
| d) Nota ética | `kpis/` | `nota-etica-ia.md` |
| e) Reflexão | `kpis/` | `reflexao-final.md` |

```dataview
TABLE file.mtime as "Atualizado"
FROM "docs/entregaveis/criativos"
SORT file.name ASC
```

```dataview
TABLE file.mtime as "Atualizado"
FROM "docs/entregaveis/kpis"
SORT file.name ASC
```

## Vault Atualizado Atv1+Atv2+Atv3 (8h)

- `00-07` Atv1 (3h15) + `08-13` Atv2 (2h) + `14-20` Atv3 (1h45) = dia 8h completo `[[03-cronograma]]`
- `templates/` 12 arquivos: 4 Atv1 + 3 Atv2 + 5 Atv3 (`peca-comunicacao`, `conceito-visual`, `kpis-4-indicadores`, `nota-etica-ia`, `reflexao-final`)
- `entregaveis/` 7 pastas: `personas`, `jornada_cliente`, `propostaspersonalizacao`, `gatilhos`, `calendario`, `criativos`*, `kpis`* (*novas)
- Landing `analisepublico.html` (Atv1) + `analisecompleta.html` + `justificativas.html` (Atv2) — **não atualizado** conforme escolha 3

---
> [!SUCCESS] Vault pronto para Atv3
> Comece por [[15-tarefas-criativos|15]] → `criativos/` e `kpis/`.

#checklist #atv3
