---
aliases: ["Grão Vivo", "Perfil da Empresa", "Quadro 2"]
tags: [senai, marketing-digital, grao-vivo, persona, quadro2, estudo-de-caso, atividade1, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx
prev: "[[01-instrucoes-e-capacidades|01 — Instruções]]"
next: "[[03-cronograma|03 — Cronograma]]"
empresa: Grão Vivo
ticket: "R$ 45,00"
seguidores: 8200
---

# 02 — Perfil da Empresa Grão Vivo (Quadro 2)

> [!QUOTE] Fonte literal — `Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx:19-20` + `TABLE 1`
> `2 SITUAÇÃO DE APRENDIZAGEM`

## 2.1 Situação de Aprendizagem (citação literal)

> [!QUOTE] `Atividade_1_...docx:19`
> `A Grão Vivo é uma torrefadora e loja virtual de cafés especiais que atua há dois anos por meio de uma feira física semanal e de vendas via WhatsApp. Com o objetivo de profissionalizar sua presença digital, a empresa contratou você, e sua turma, como consultoria júnior de marketing digital para planejar, com apoio de Inteligência Artificial, o lançamento de uma nova linha de cafés especiais. O Quadro 2 apresenta as informações que a empresa passou.`

> [!QUOTE] `Quadro 2 – Perfil da empresa Grão Vivo` — `Atividade_1_...docx:20`

## 2.2 Quadro 2 — Transcrição Fiel

| Aspecto | Informação disponibilizada pelo cliente |
|---|---|
| **Canais atuais** | `Instagram (8.200 seguidores), WhatsApp Business e feira física aos sábados.` |
| **Ticket médio** | `R$ 45,00.` |
| **Perfil de quem já compra** | `majoritariamente entre 28 e 45 anos, moradores da região.` |
| **Dado relevante** | `cerca de 60% dos seguidores no Instagram nunca realizaram uma compra.` |
| **Reclamação recorrente** | `dificuldade dos clientes em escolher entre os tipos de café oferecidos.` |
| **Comentários captados nas redes sociais** | `“Sigo a página faz tempo, mas nunca sei qual café combina comigo.”` <br> `“Vi um preço parecido em outro lugar e fiquei em dúvida se vale a pena aqui.”` <br> `“Queria comprar, mas não vi ninguém comentando se é bom.”` <br> `“Mandei mensagem no WhatsApp perguntando sobre um produto e demorou pra responder.”` |
| **Nova linha de produto** | `cafés especiais de torra média, posicionados como produto premium.` |
| **Meta da campanha de lançamento** | `aumentar em 20% as vendas digitais no primeiro mês.` |

> [!NOTE] Fonte
> `TABLE 1` do .docx. Use este quadro como `Contexto do cliente` no prompt — ver [[06-guia-ia-e-prompts#Modelo de Prompt|modelo de prompt]].

## 2.3 Leitura Analítica — O que cada dado sinaliza (tarefa a)

> [!IMPORTANT] Para a tarefa (a) `analisar o perfil da empresa Grão Vivo apresentado no Quadro 2` — `Atividade_1_...docx:30`

| Dado | Insight para persona / jornada | Tarefa impactada |
|---|---|---|
| **8.200 seguidores, 60% nunca comprou (~4.920 pessoas)** | Público frio grande = foco da atividade. Persona deve refletir seguidor não-comprador, não cliente fiel. | [[templates/persona\|persona]] |
| **WhatsApp Business + IG + feira sábado** | Jornada híbrida: descoberta no IG, dúvida no WhatsApp, prova na feira. Gargalo no SLA. | [[templates/jornada-cliente\|jornada]] |
| **Ticket R$45** | Premium acessível. Sensível a preço/valor ("vi preço parecido..."). | persona.motivação |
| **28-45 anos, região** | Base demográfica — não invente 18 ou 60 anos sem justificar. | persona.demográfico |
| **Dificuldade de escolha** | Dor central → quiz, recomendação, chatbot consultivo. | [[templates/proposta-personalizacao\|proposta]] |
| **4 comentários** | 4 dores/gatilhos: 1) falta de personalização, 2) comparação preço/valor, 3) falta de prova social, 4) SLA atendimento. | jornada.etapas |
| **Torra média premium** | Posicionamento — valoriza qualidade/sensorial ou status. | persona.motivação |

> [!TIP] Dataview — filtrar comentários por dor
> ```dataview
> TABLE dor, gatilho
> FROM "docs/templates"
> WHERE dor
> ```

## 2.4 Checklist de Coerência (para revisar personas na tarefa c)

> [!QUESTION] Tarefa (c) `revisar as personas geradas pela IA e corrigir informações que não combinem com o perfil do cliente apresentado` — `Atividade_1_...docx:32`

- [ ] Idade da persona entre 28-45 ou justificada se fora?
- [ ] Mora na região (ex: Registro/SP, Vale do Ribeira)?
- [ ] Segue no IG mas nunca comprou — comportamento digital compatível?
- [ ] Dor inclui `não sei qual café combina comigo` ou variação?
- [ ] Ticket R$45 é plausível para renda/estilo de vida?
- [ ] Nova linha torra média premium faz sentido para motivação?
- [ ] Não contradiz canais (ex: persona que "odeia Instagram" não faz sentido)?

> [!WARNING] Erro comum (CSE2) — viés da IA
> IA tende a criar `Mariana, 22 anos, estudante de SP capital, ama café gourmet importado` — generalização excessiva e **incoerente** com `28-45 anos, moradores da região` e `feira física aos sábados`.

## 2.5 Como usar este perfil nas tarefas

| Tarefa | Uso deste quadro |
|---|---|
| **(a)** | Analise e anote 3 oportunidades + 3 riscos |
| **(b)** | Cole este quadro no prompt como `Contexto do cliente` → [[06-guia-ia-e-prompts]] |
| **(c)** | Volte aqui para corrigir a IA (checklist acima) |
| **(d)** | Jornada deve resolver as 4 dores dos comentários em Descoberta/Consideração/Decisão |
| **(e)** | Ferramenta deve atacar `dificuldade de escolha` + `demora no WhatsApp` |

---

> [!SUCCESS] Próximo passo
> [[03-cronograma|03 — Cronograma]] para planejar seu tempo nas 3h15.

#grao-vivo #quadro2 #estudo-de-caso
