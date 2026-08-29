---
aliases: ["Entregável", "Critérios de Avaliação", "Rubrica"]
tags: [senai, entregavel, avaliacao, criterios, rubrica, atividade1, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx
prev: "[[04-tarefas-passo-a-passo|04 — Tarefas]]"
next: "[[06-guia-ia-e-prompts|06 — Guia IA]]"
---

# 05 — Entregável e Critérios de Avaliação

> [!QUOTE] Fonte literal — `Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx:38-45` + `TABLE 3`
> `4.4 Entregável` / `4.5 Critérios de Avaliação`

## 4.4 Entregável (citação literal)

> [!QUOTE] `Atividade_1_...docx:39`
> `Documento (Word, PDF ou apresentação) contendo:`

> [!IMPORTANT] Conteúdo obrigatório — `Atividade_1_...docx:40-43`
> `a) 2 (duas) personas completas;`
> `b) jornada do cliente de cada persona;`
> `c) proposta de ferramenta de personalização, com justificativa;`
> `d) prompt(s) utilizado(s) na ferramenta de IA.`

### Detalhamento do que cada item deve conter

| Item | O que é "completo" | Template Obsidian |
|---|---|---|
| **a) 2 personas** | Dados demográficos + comportamento digital + dores + motivações de compra (coerentes com [[02-perfil-grao-vivo|Quadro 2]]) | [[templates/persona\|persona.md]] |
| **b) Jornada** | Para **cada** persona, 3 etapas: descoberta, consideração, decisão (com touchpoints) | [[templates/jornada-cliente\|jornada-cliente.md]] |
| **c) Proposta** | Ferramenta (chatbot/assistente/recomendação) + justificativa com dados/ML | [[templates/proposta-personalizacao\|proposta-personalizacao.md]] |
| **d) Prompt(s)** | Prompt(s) na íntegra + ferramenta + data | [[templates/registro-prompts\|registro-prompts.md]] |

> [!TIP] Formato de entrega
> Word, PDF ou apresentação — exporte de `entregaveis/`. Nome sugerido: `Entrega_Atividade1_Persona_Nome_Sobrenome_2026.pdf`

---

## 4.5 Critérios de Avaliação (cópia fiel — `TABLE 3`)

> [!QUOTE] `Atividade_1_...docx:45` — `TABLE 3` transcrita literalmente

| Critérios Críticos | Critérios Desejáveis |
|---|---|
| `a) apresenta 2 (duas) personas com dados coerentes ao perfil de cliente da Grão Vivo (Quadro 2);` | `a) propõe indicadores iniciais para validar as personas construídas;` |
| `b) descreve a jornada do cliente nas 3 (três) etapas solicitadas para cada persona;` | `b) aponta, com senso crítico, limitações da IA na criação das personas (viés ou generalização excessiva);` |
| `c) mostra o uso de Inteligência Artificial generativa no processo, com o(s) prompt(s) registrado(s);` | `c) apresenta proposta de personalização que vai além do mínimo solicitado.` |
| `d) justifica a escolha da ferramenta de personalização com base em análise de dados ou aprendizado de máquina.` |  |

### Rubrica — Como se autoavaliar (Obsidian tasks)

> [!EXAMPLE] Use como checklist antes de entregar

#### Critérios Críticos (elimina se faltar)

- [ ] **CC-a** 2 personas coerentes com [[02-perfil-grao-vivo|Quadro 2]] (28-45, região, 60% nunca comprou, torra média premium) #criterio/critico
- [ ] **CC-b** Jornada 3 etapas para cada persona (descoberta/consideração/decisão) #criterio/critico
- [ ] **CC-c** Prompt(s) registrado(s) na íntegra + evidência de uso de IA generativa #criterio/critico
- [ ] **CC-d** Justificativa com dados/ML (não só "achei legal") #criterio/critico

#### Critérios Desejáveis (diferencial)

- [ ] **CD-a** Indicadores para validar personas (ex: taxa conversão por persona, CTR IG, NPS, pesquisa) #criterio/desejavel
- [ ] **CD-b** Limitações da IA apontadas (viés, generalização excessiva) #criterio/desejavel
- [ ] **CD-c** Proposta além do mínimo (ex: quiz + chatbot + e-mail segmentado) #criterio/desejavel

> [!WARNING] Reprovação por crítico
> Faltar **um** critério crítico = entrega incompleta. Desejáveis elevam nota, mas não compensam falta de crítico.

## 📊 Matriz de Evidências por Capacidade

| Capacidade | Critério que evidencia | Onde no documento |
|---|---|---|
| **CT2** (ferramentas IA para dados) | CC-d | Proposta → justificar ML |
| **CT4** (experiência + personalização) | CC-b + CC-d | Jornada + proposta |
| **CSE1** (visão sistêmica) | CC-a + CC-b | Coerência Quadro 2 → persona → jornada |
| **CSE2** (senso crítico) | CC-c + CD-b | Registro + crítica à IA |

> [!QUESTION] Autoavaliação — 3 perguntas
> 1. Minhas personas passariam no [[02-perfil-grao-vivo#2.4 Checklist de Coerência|checklist Grão Vivo]]?
> 2. Minha justificativa menciona **dado + algoritmo + métrica**?
> 3. Meu documento tem **prompt literal** copiado?

## 📤 Onde entregar

- Pasta: `docs/entregaveis/` (vazia — coloque seu PDF/Word lá)
- Também entregue conforme orientação do instrutor em sala (físico ou AVA)
- Data: `_____ / _____ / 2026` — `Atividade_1_...docx:14` (até 13h00 do dia da aula)

```dataview
TABLE file.mtime as "Última atualização"
FROM "docs/entregaveis"
SORT file.mtime DESC
```

---

> [!SUCCESS] Próximo passo
> [[06-guia-ia-e-prompts|06 — Guia de IA e Prompts]] para garantir CC-c e CC-d.

#entregavel #avaliacao #rubrica
