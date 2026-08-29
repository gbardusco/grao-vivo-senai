---
aliases: ["Guia IA", "Prompts - Persona", "Uso de IA Generativa"]
tags: [senai, ia, prompt, prompt-engineering, gemini, chatgpt, persona, atividade1, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx
prev: "[[05-entregavel-e-avaliacao|05 — Entregável]]"
next: "[[07-checklist-e-templates|07 — Checklist]]"
---

# 06 — Guia de IA Generativa e Prompts

> [!QUOTE] Fonte literal — `Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx:36-37`
> `4.3 Uso de Inteligência Artificial`
> `Usar uma ferramenta de Inteligência Artificial generativa (sugestão: Gem personalizado no Gemini, ChatGPT ou Copilot) para ajudar a criar as personas, escrevendo o(s) prompt(s) e registrando-o(s) por completo no documento de entrega.` — `Atividade_1_...docx:37`

> [!IMPORTANT] Uso obrigatório
> Tarefa (b) exige `contexto do cliente, objetivo da persona e formato de saída` — `Atividade_1_...docx:31`. Sem registrar, reprova critério **CC-c** → [[05-entregavel-e-avaliacao#Critérios Críticos (elimina se faltar)|CC-c]].

## 6.1 Ferramentas Sugeridas

| Ferramenta | Por que usar | Link Obsidian |
|---|---|---|
| **Gem personalizado no Gemini** | Sugestão literal do documento | `gemini.google.com` |
| **ChatGPT** | Ótimo para personas + iteração rápida | `chat.openai.com` |
| **Copilot** | Integração Microsoft, bom para tabelas | `copilot.microsoft.com` |

> [!TIP] Qualquer IA generativa serve
> Desde que você **registre o prompt** em [[templates/registro-prompts|registro-prompts.md]]. Use a que tiver conta.

## 6.2 Estrutura Obrigatória do Prompt (3 elementos)

> [!QUOTE] `Atividade_1_...docx:31`
> `escrever um prompt com contexto do cliente, objetivo da persona e formato de saída`

| Elemento | O que deve conter | Exemplo literal Grão Vivo |
|---|---|---|
| **1. Contexto do cliente** | Cole [[02-perfil-grao-vivo#2.2 Quadro 2 — Transcrição Fiel|Quadro 2]] completo (8.200 seguidores, R$45, 28-45 anos, 60% nunca comprou, 4 comentários, torra média premium, +20%) | `Você é consultor da Grão Vivo: torrefadora...` |
| **2. Objetivo da persona** | Para quem e para quê | `Gerar 2 personas de seguidores IG que nunca compraram, para personalizar lançamento torra média premium, meta +20% vendas digitais` |
| **3. Formato de saída** | Estrutura exigida | `dados demográficos, comportamento digital, dores e motivações de compra` + `jornada em tabela` se quiser |

## 6.3 Modelo de Prompt — Copiar e Colar

> [!EXAMPLE] Prompt Base (copie para sua IA)

````markdown
# CONTEXTO DO CLIENTE — Grão Vivo
Você é consultor(a) júnior de marketing digital contratado pela Grão Vivo:
- Torrefadora e loja virtual de cafés especiais, 2 anos, canais: Instagram (8.200 seguidores), WhatsApp Business e feira física aos sábados.
- Ticket médio: R$ 45,00.
- Quem já compra: majoritariamente 28-45 anos, moradores da região.
- Dado crítico: cerca de 60% dos seguidores no Instagram nunca realizaram uma compra.
- Reclamação recorrente: dificuldade em escolher entre os tipos de café.
- Comentários reais:
  1. "Sigo a página faz tempo, mas nunca sei qual café combina comigo."
  2. "Vi um preço parecido em outro lugar e fiquei em dúvida se vale a pena aqui."
  3. "Queria comprar, mas não vi ninguém comentando se é bom."
  4. "Mandei mensagem no WhatsApp perguntando sobre um produto e demorou pra responder."
- Nova linha: cafés especiais torra média, posicionados como produto premium.
- Meta: aumentar em 20% as vendas digitais no primeiro mês.

# OBJETIVO DA PERSONA
Gere 2 (duas) personas distintas que representem seguidores do Instagram que AINDA NÃO compraram, para personalizar a experiência antes do lançamento. Foque no público 28-45 da região.

# FORMATO DE SAÍDA (obrigatório)
Para cada persona, entregue em tabela:
| Campo | Persona 1 | Persona 2 |
| Nome fictício | | |
| Idade / Cidade / Profissão | 28-45, região |  |
| Dados demográficos | | |
| Comportamento digital (IG/WhatsApp) | | |
| Dores (2-3, ligadas aos 4 comentários) | | |
| Motivações de compra (2-3) | | |
| Gatilho que converteria | | |

Restrições: não invente dados fora da região; ticket R$45 deve ser plausível; cite qual comentário cada dor endereça.
````

> [!TIP] No Obsidian
> Selecione o bloco acima → `Ctrl+C` → cole na sua IA. Depois cole o resultado em [[templates/persona|persona.md]] e revise com [[02-perfil-grao-vivo#2.4 Checklist de Coerência|checklist]].

## 6.4 Segundo Prompt — Jornada (encadeado)

> [!EXAMPLE] Prompt para tarefa (d) — após gerar personas

```markdown
Com base nas 2 personas que você gerou para a Grão Vivo, mapeie a jornada do cliente para CADA persona nas 3 etapas: descoberta, consideração e decisão.

Para cada etapa, informe em tabela:
Etapa | Ação da persona | Pensamento/Sentimento | Touchpoint (IG/WhatsApp/Feira) | Oportunidade de personalização

Conecte cada etapa às dores dos 4 comentários originais.
```

## 6.5 Como Registrar (tarefa f)

> [!QUOTE] `Atividade_1_...docx:35`
> `f) registrar, no documento de entrega, o(s) prompt(s) utilizado(s) na ferramenta de IA.`

> [!WARNING] Registro incompleto = reprova CC-c
> Inclua:
> - [ ] Prompt(s) na íntegra (copiar/colar literal) #registro
> - [ ] Ferramenta + versão (ex: `ChatGPT-4o 2026-08-29`)
> - [ ] Data/hora
> - [ ] Link para conversa se houver
> - [ ] O que você corrigiu após a IA (evidência CSE2)

Use [[templates/registro-prompts|registro-prompts.md]] — já está com frontmatter Obsidian.

## 6.6 Boas Práticas e Limitações da IA (para CD-b)

> [!QUESTION] O que apontar como limitação (critério desejável b)
> `aponta, com senso crítico, limitações da IA na criação das personas (viés ou generalização excessiva)` — `TABLE 3`

| Limitação | Exemplo Grão Vivo |
|---|---|
| **Viés de idade/riqueza** | IA cria persona jovem rica de capital, fora dos 28-45 região |
| **Generalização** | "Gosta de café" sem especificar dor real dos 4 comentários |
| **Alucinação** | Inventa canal TikTok que não existe no Quadro 2 |
| **Estereótipo** | Persona sempre "empreendedora fitness" — clichê |

> [!NOTE] Como demonstrar CSE2
> No documento final, adicione seção `## Limitações da IA` com 3–4 linhas: o que a IA gerou errado e como você corrigiu.

## 6.7 Checklist de Prompt

- [ ] Contém Quadro 2 completo como contexto? #prompt
- [ ] Objetivo menciona 60% nunca comprou + torra média premium + meta +20%?
- [ ] Formato pede demográfico + comportamento digital + dores + motivações?
- [ ] Gerei 2 personas distintas (não cópias)?
- [ ] Salvei prompt + output em [[templates/registro-prompts|registro]]?

---

> [!SUCCESS] Próximo passo
> [[07-checklist-e-templates|07 — Checklist e Templates]] para montar o documento final.

#prompt #ia-generativa #gemini
