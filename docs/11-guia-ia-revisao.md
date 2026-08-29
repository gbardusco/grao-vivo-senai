---
aliases: ["IA Revisão Lógica", "Prompt Calendário"]
tags: [senai, ia, prompt, revisao, calendario, atividade2, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_2_Aluno_Neuromarketing_e_Calendario_de_Conteudo.docx
prev: "[[10-calendario-conteudo|10 — Calendário]]"
next: "[[12-entregavel-avaliacao-atv2|12 — Entregável Atv2]]"
---

# 11 — Guia IA: Revisar Lógica do Calendário

> [!QUOTE] Fonte — `Atividade_2_Aluno_Neuromarketing_e_Calendario_de_Conteudo.docx:33-36`
> `d) usar uma Inteligência Artificial generativa para revisar e melhorar a lógica do calendário (a relação entre gatilho mental, canal e etapa do funil), registrando o prompt usado e avaliando criticamente a resposta;` — `Atividade_2_...docx:33`
> `4.3 Uso de Inteligência Artificial — Usar uma IA generativa para revisar e melhorar a lógica do calendário de conteúdo (a relação entre gatilho mental, canal e etapa do funil), registrando o prompt usado e avaliando criticamente a resposta.` — `Atividade_2_...docx:36`

> [!IMPORTANT] Crítico d — `TABLE 3` Atv2
> `mostra o uso da IA generativa (prompt e resultado) e a revisão crítica da lógica do calendário.`

## O que a IA deve revisar

- Coerência **gatilho ↔ canal ↔ funil** (ex: dopamina no Reels topo faz sentido? ancoragem no WhatsApp fundo faz?)
- Sistema 1 vs 2 correto
- Persona certa (Ana curadoria vs Rafael valor)

## Modelo de Prompt — Copiar e Colar (Atv2)

> [!EXAMPLE] Prompt revisão

````markdown
# CONTEXTO — Grão Vivo (reaproveite Atv1)
- Personas: Ana Clara 34 Registro/SP (curadoria, “não sei qual combina”) e Rafael 38 Pariquera-Açu (valor, “vale a pena? + prova social”) — ver docs/entregaveis/personas/
- Quadro 2: 8.200 seguidores IG, 60% nunca comprou, ticket R$45, torra média premium, canais IG/WhatsApp/feira
- Situação Atv2: anúncios racionais puros converteram pouco no fundo; precisa calendário neuromarketing semana lançamento

# CALENDÁRIO PARA REVISAR
| # | Canal | Funil | Gatilho | Persona |
| 1 | IG Reels | Topo | Dopamina (S1) | Ana |
| 2 | IG Carrossel + WhatsApp | Meio | Reciprocidade S1 / Ancoragem S2 | Ana/Rafael |
| 3 | WhatsApp + Feira sábado | Fundo | Escassez/Urgência S1 + Identidade S1 | Ambas |

# TAREFA DA IA
Revise e melhore a lógica: gatilho→canal→funil está coerente? Classifique cada gatilho em Sistema 1 ou 2. Sugira 1 melhoria por postagem e 1 risco ético. Responda em tabela.

# FORMATO
| Post | Coerência (sim/não) | S1/S2 correto? | Melhoria | Risco ético |
````

> [!TIP] Onde colar: Gemini/ChatGPT/Copilot — salvar em `[[templates/registro-prompts|registro-prompts]]` + `docs/entregaveis/registro-prompts.md`

## Como Avaliar Criticamente a Resposta (CSE2)

> [!QUESTION] Checklist avaliação crítica — 4 perguntas
> 1. A IA acertou S1/S2? (ex: prova social é S1, não S2)
> 2. A lógica canal-funil faz sentido? (ex: escassez combina com fundo+WhatsApp, não topo)
> 3. Sugeriu melhoria plausível ou genérica?
> 4. Apontou risco ético (persuasão vs manipulação)? — ver `TABLE 3` desejável b

| Avaliação | O que escrever no entregável |
|---|---|
| `Concordância` | `Concordo: dopamina no Reels topo ativa S1 rápido, ok.` |
| `Correção` | `Discordo: IA pôs ancoragem no fundo — correto é meio, onde compara preço.` |
| `Crítica ética` | `Escassez real (40 unidades) é ética; criar falsa urgência seria manipulação.` |

> [!WARNING] Erro comum IA
> Confundir `S1 dopamina` com S2 ou sugerir `WhatsApp para topo` (topo é IG Reels, não WhatsApp 1:1).

### Checklist

- [ ] Prompt com contexto Atv1 + calendário 3 posts + tarefa revisão #prompt
- [ ] Resposta IA salva na íntegra #registro
- [ ] Avaliação crítica 3-4 linhas com concordância/correção/ética #criterio/critico

---
> [!SUCCESS] Próximo
> [[12-entregavel-avaliacao-atv2|12 — Entregável Atv2]] + `[[templates/justificativa-s1-s2|justificativa]]`.

#ia #revisao #prompt
