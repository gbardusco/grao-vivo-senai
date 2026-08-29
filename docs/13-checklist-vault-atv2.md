---
aliases: ["Checklist Atv2", "Revisão Final Atv2"]
tags: [senai, checklist, atividade2, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_2_Aluno_Neuromarketing_e_Calendario_de_Conteudo.docx
prev: "[[12-entregavel-avaliacao-atv2|12 — Entregável Atv2]]"
next: "[[README|README]]"
---

# 13 — Checklist Final e Vault — Atividade 2

> [!QUOTE] Fonte consolidada — `Atividade_2_Aluno_Neuromarketing_e_Calendario_de_Conteudo.docx:38-44` + `TABLE 3`

## Checklist Críticos Atv2

- [ ] ≥3 gatilhos distintos por persona com S1/S2 correto (CC-a/b) — `[[09-tarefas-gatilhos-funil]]` #criterio/critico
- [ ] Matriz persona×funil topo/meio/fundo preenchida #criterio/critico
- [ ] Calendário 3 posts: canal IG/WhatsApp/feira + funil + gatilho coerentes (CC-c) — `[[10-calendario-conteudo]]` #criterio/critico
- [ ] Prompt IA revisão + resposta + avaliação crítica 3-4 linhas (CC-d) — `[[11-guia-ia-revisao]]` #criterio/critico
- [ ] Justificativa S1/S2 por que aumenta conversão (item d) — `[[templates/justificativa-s1-s2|justificativa]]` #criterio/critico
- [ ] Reaproveitou `[[../entregaveis/personas/persona-01-indecisa-curadoria|Ana]]` e `[[../entregaveis/personas/persona-02-comparador-valor|Rafael]]` Atv1 #reaproveitamento

## Desejáveis (diferencial)

- [ ] Perfis Esperançosos/Autônomos/Imparciais/Sinérgicos relacionados #desejavel
- [ ] Riscos éticos persuasão vs manipulação discutidos #desejavel
- [ ] Métrica por postagem (CTR, tempo, conversão) #desejavel

## Entregáveis Atv2 — Pastas

| Entregável | Pasta | Arquivo exemplo |
|---|---|---|
| a) Gatilhos | `docs/entregaveis/gatilhos/` | `gatilhos-ana-rafael.md` |
| b) Calendário | `docs/entregaveis/calendario/` | `calendario-3-posts.md` |
| c) Prompt+crítica | `docs/entregaveis/registro-prompts.md` | Prompt 13+ |
| d) Justificativa S1/S2 | `docs/entregaveis/gatilhos/` ou `calendario/` | `justificativa-s1-s2.md` |

```dataview
TABLE file.mtime as "Atualizado"
FROM "docs/entregaveis/gatilhos" 
SORT file.name ASC
```

```dataview
TABLE file.mtime as "Atualizado"
FROM "docs/entregaveis/calendario"
SORT file.name ASC
```

## Vault Atualizado Atv1+Atv2

- `00-07` Atv1 manhã + `08-13` Atv2 tarde = dia 8h completo `[[03-cronograma]]`
- `templates/` 7 arquivos: 4 Atv1 + 3 novos Atv2 (`gatilhos-por-persona`, `calendario-3-posts`, `justificativa-s1-s2`)
- Landing `analisepublico.html` (Atv1) → atualizar nav para linkar Atv2 após desenvolvimento

---
> [!SUCCESS] Tudo pronto para desenvolver Atv2
> Comece por [[09-tarefas-gatilhos-funil|09]] → `gatilhos/`.

#checklist #atv2
