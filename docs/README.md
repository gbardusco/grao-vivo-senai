---
aliases: ["Índice Atividade 1", "Mapa - Persona e Experiência"]
tags: [senai, marketing-digital, ia, persona, experiencia-cliente, atividade1, indice, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx
---

# Atividade 1 — Da Persona à Experiência do Cliente — Índice

> [!QUOTE] Fonte literal
> `Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx` — SENAI-SP, 2026. Autor: `Gabriel Guimarães Carneiro` — `Instrutor – SENAI-SP` — `Registro – SP`.

> [!INFO] Sobre este vault
> Este diretório `docs/` é o **breakdown completo** da Atividade 1 em arquitetura granular `kebab-case` numerada, já no **padrão Obsidian** (frontmatter YAML, callouts, wikilinks e dataview). Todas as citações são **literais** do documento original. Cada arquivo tem escopo único.

## 🗂️ Estrutura do Vault

```text
docs/
├── README.md                          # ← você está aqui
├── 00-visao-geral.md
├── 01-instrucoes-e-capacidades.md
├── 02-perfil-grao-vivo.md
├── 03-cronograma.md
├── 04-tarefas-passo-a-passo.md
├── 05-entregavel-e-avaliacao.md
├── 06-guia-ia-e-prompts.md
├── 07-checklist-e-templates.md
├── templates/
│   ├── persona.md
│   ├── jornada-cliente.md
│   ├── proposta-personalizacao.md
│   └── registro-prompts.md
└── entregaveis/
    └── .gitkeep
```

## 🧭 Navegação por Escopo

| # | Arquivo | Quando usar | Fonte |
|---|---|---|---|
| `00` | [[00-visao-geral\|00 — Visão Geral]] | Entender o que é a atividade, duração e palavras-chave | `Atividade_1_...docx:10-12` |
| `01` | [[01-instrucoes-e-capacidades\|01 — Instruções e Capacidades]] | Regras, registro de prompts e capacidades CT2/CT4/CSE1/CSE2 | `Atividade_1_...docx:15-17` |
| `02` | [[02-perfil-grao-vivo\|02 — Perfil Grão Vivo]] | Analisar o cliente antes de criar personas | `Atividade_1_...docx:19-20` |
| `03` | [[03-cronograma\|03 — Cronograma]] | Gerenciar tempo dentro do bloco de 3h15 da manhã | `Atividade_1_...docx:21-23` |
| `04` | [[04-tarefas-passo-a-passo\|04 — Tarefas Passo a Passo]] | Executar cada tarefa a–f sem pular etapas | `Atividade_1_...docx:30-35` |
| `05` | [[05-entregavel-e-avaliacao\|05 — Entregável e Avaliação]] | Conferir o que deve conter no documento final | `Atividade_1_...docx:38-43` + `TABLE 3` |
| `06` | [[06-guia-ia-e-prompts\|06 — Guia de IA e Prompts]] | Escrever prompts com contexto+objetivo+formato | `Atividade_1_...docx:36-37` |
| `07` | [[07-checklist-e-templates\|07 — Checklist e Templates]] | Revisão final antes da entrega | Consolidado |

> [!TIP] Fluxo recomendado no Obsidian
> 1. Leia na ordem `[[00-visao-geral]]` → `[[03-cronograma]]` para contextualização (15 min).
> 2. Execute a atividade seguindo [[04-tarefas-passo-a-passo]] e usando os [[07-checklist-e-templates#Templates|templates]].
> 3. Valide com [[05-entregavel-e-avaliacao]] e [[07-checklist-e-templates#Checklist Final|checklist]].
> 4. Exporte o documento final de `entregaveis/` (Word, PDF ou apresentação).

## 🔗 Graph View — Relações

- [[00-visao-geral]] → [[01-instrucoes-e-capacidades]] → [[02-perfil-grao-vivo]] → [[04-tarefas-passo-a-passo]]
- [[04-tarefas-passo-a-passo]] ↔ [[06-guia-ia-e-prompts]]
- [[04-tarefas-passo-a-passo]] → [[05-entregavel-e-avaliacao]] ← [[07-checklist-e-templates]]

## 📊 Dataview — Listar todos os docs da atividade

```dataview
TABLE tags, created, source
FROM "docs"
WHERE contains(tags, "atividade1")
SORT file.name ASC
```

```dataview
TASK
FROM "docs"
WHERE !completed
GROUP BY file.link
```

## 🎨 Convenções Obsidian

- **Frontmatter YAML** em todos os arquivos → compatível com Dataview, Graph e Properties.
- **Citações literais** em `> [!QUOTE]` com referência `Atividade_1_...docx:linha`.
- **Callouts** para alertas: `!NOTE`, `!IMPORTANT`, `!WARNING`, `!TIP`, `!EXAMPLE`, `!QUESTION`.
- **Wikilinks** `[[arquivo|label]]` para navegação e Graph View. Evite markdown links `[x](y)`.
- **Tasks** `- [ ]` clicáveis no Obsidian.
- **Tags** `#senai #marketing-digital #persona` para busca.

## 📚 Referências

Ver [[00-visao-geral#Referências (cópia literal)|Referências completas]] — `Atividade_1_...docx:47-49`.

---

> [!SUCCESS] Próximo passo
> Abra [[00-visao-geral|00 — Visão Geral]] para começar.

#senai #indice #mapa-de-conteudo
