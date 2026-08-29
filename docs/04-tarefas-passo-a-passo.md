---
aliases: ["Tarefas a-f", "Passo a Passo"]
tags: [senai, tarefas, passo-a-passo, persona, jornada, personalizacao, atividade1, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx
prev: "[[03-cronograma|03 — Cronograma]]"
next: "[[05-entregavel-e-avaliacao|05 — Entregável]]"
---

# 04 — Tarefas Passo a Passo (a–f)

> [!QUOTE] Fonte literal — `Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx:27-35`
> `4 ATIVIDADE 1 – DA PERSONA À EXPERIÊNCIA DO CLIENTE`
> `Turno: Manhã   |   Duração: 3h15 (com intervalo de 10h45 às 11h00)   |   Modalidade: Individual` — `Atividade_1_...docx:26`

## 4.1 Situação-problema (citação literal)

> [!WARNING] Problema a resolver — `Atividade_1_...docx:28`
> `A Grão Vivo não sabe exatamente quem são os seguidores das redes sociais que ainda não compraram, nem como personalizar a experiência de compra desse público antes do lançamento da nova linha de cafés.`

> [!QUESTION] Pergunta-guia
> Quem são esses ~4.920 seguidores (60% de 8.200) que nunca compraram e como personalizar a experiência deles para converter no lançamento da torra média premium?

---

## 4.2 Tarefas — Decomposição Operacional

### Tarefa (a) — Analisar o perfil da empresa

> [!QUOTE] `Atividade_1_...docx:30`
> `a) analisar o perfil da empresa Grão Vivo apresentado no Quadro 2;`

> [!NOTE] O que fazer
> Leia [[02-perfil-grao-vivo|Quadro 2]] e extraia:
> - **Oportunidades:** público frio grande, prova na feira, ticket acessível
> - **Riscos:** SLA WhatsApp, falta de prova social, dificuldade de escolha

> [!EXAMPLE] Saída esperada
> Tabela ou mapa mental com 3 oportunidades + 3 riscos + citação dos 4 comentários.

- [ ] Li [[02-perfil-grao-vivo#2.2 Quadro 2 — Transcrição Fiel|Quadro 2]] na íntegra #tarefa/a
- [ ] Anotei 3 oportunidades e 3 riscos

### Tarefa (b) — Escrever prompt e gerar 2 personas com IA

> [!QUOTE] `Atividade_1_...docx:31`
> `b) escrever um prompt com contexto do cliente, objetivo da persona e formato de saída, e usá-lo em uma ferramenta de Inteligência Artificial generativa para gerar 2 (duas) personas, com dados demográficos, comportamento digital, dores e motivações de compra;`

> [!IMPORTANT] Estrutura obrigatória do prompt
> `contexto do cliente` + `objetivo da persona` + `formato de saída` — `Atividade_1_...docx:31`

| Elemento | O que incluir |
|---|---|
| **Contexto** | Cole [[02-perfil-grao-vivo#2.2 Quadro 2 — Transcrição Fiel|Quadro 2]] completo |
| **Objetivo** | `Gerar 2 personas de seguidores IG que nunca compraram, para personalizar lançamento torra média premium, meta +20% vendas digitais` |
| **Formato** | `dados demográficos, comportamento digital, dores e motivações de compra` |

> [!TIP] Ferramentas sugeridas — `Atividade_1_...docx:37`
> `Gem personalizado no Gemini, ChatGPT ou Copilot` — ver [[06-guia-ia-e-prompts]] para modelos prontos.

> [!EXAMPLE] Template de prompt em [[06-guia-ia-e-prompts#Modelo de Prompt — Copiar e Colar|06 — Guia de IA]]

- [ ] Escrevi prompt com os 3 elementos obrigatórios #tarefa/b
- [ ] Gerei 2 personas na IA e salvei output bruto

> [!WARNING] 2 personas ≠ 1 persona duplicada
> Crie perfis distintos que cubram dores diferentes dos 4 comentários (ex: uma com dor de escolha, outra com dor de prova social/preço).

### Tarefa (c) — Revisar e corrigir personas

> [!QUOTE] `Atividade_1_...docx:32`
> `c) revisar as personas geradas pela IA e corrigir informações que não combinem com o perfil do cliente apresentado;`

> [!FAIL] O que corrigir — viés da IA (CSE2)
> - Idade fora de 28-45 sem justificativa
> - Local fora da região
> - Comportamento digital incompatível (ex: "não usa Instagram")
> - Ticket R$45 incompatível com renda
> - Nova linha torra média ignorada

> [!NOTE] Checklist de coerência
> Use [[02-perfil-grao-vivo#2.4 Checklist de Coerência|02 — Checklist de Coerência]] — marque cada item para as 2 personas.

- [ ] Revisei persona 1 com checklist [[02-perfil-grao-vivo#2.4 Checklist de Coerência|Grão Vivo]] #tarefa/c
- [ ] Revisei persona 2 com checklist
- [ ] Registrei o que corrigi e por quê (evidência CSE2)

> [!TIP] Registre a correção no documento final — mostra `senso crítico`.

### Tarefa (d) — Mapear jornada do cliente (3 etapas)

> [!QUOTE] `Atividade_1_...docx:33`
> `d) mapear, para cada persona, a jornada do cliente nas etapas de descoberta, consideração e decisão;`

| Etapa | Pergunta-guia | Exemplo para Grão Vivo |
|---|---|---|
| **Descoberta** | Como ela descobre a Grão Vivo / nova linha? | Reels IG, indicação na feira |
| **Consideração** | O que ela compara/avalia? | Prova social, comparativo de preço, quiz "qual café combina comigo" |
| **Decisão** | O que faz ela comprar (ou desistir)? | Resposta rápida no WhatsApp, frete, kit degustação |

> [!IMPORTANT] 2 personas x 3 etapas = 6 células mínimas
> Cada célula deve conter: **ação**, **pensamento/sentimento**, **touchpoint** (IG, WhatsApp, feira), **oportunidade de personalização**.

- [ ] Mapeei jornada persona 1 (3 etapas) #tarefa/d
- [ ] Mapeei jornada persona 2 (3 etapas)
- [ ] Incluí touchpoints IG / WhatsApp / feira

> [!EXAMPLE] Template
> Use [[templates/jornada-cliente|jornada-cliente.md]] — já está em formato Obsidian com callouts e tabela.

### Tarefa (e) — Propor ferramenta de personalização

> [!QUOTE] `Atividade_1_...docx:34`
> `e) propor uma ferramenta de personalização da experiência (chatbot, assistente virtual ou motor de recomendação) e justificar a escolha com base em análise de dados e aprendizado de máquina;`

> [!QUESTION] Opções — `chatbot, assistente virtual ou motor de recomendação`
> Escolha **uma** (ou combine) e justifique com **dados/ML**, não só opinião.

| Ferramenta | Dado que alimenta | ML envolvido | Dor que resolve |
|---|---|---|---|
| **Chatbot WhatsApp** | Histórico de perguntas + SLA atual | NLP / classificação de intenção + resposta generativa | `demorou pra responder` |
| **Quiz / Motor de recomendação** | Respostas do quiz + histórico de compras | Filtragem colaborativa / content-based | `não sei qual café combina comigo` |
| **Assistente virtual no site/IG** | Comportamento navegação + 60% nunca comprou | Clustering + recomendação | `vi preço parecido, fiquei em dúvida` |
| **Prova social dinâmica** | UGC, avaliações | Sentiment analysis + ranking | `não vi ninguém comentando se é bom` |

> [!WARNING] Justificativa com dados/ML é critério crítico (d)
> Explique: **qual dado** coleta, **qual algoritmo** (ex: NLP, recomendação), **qual métrica** de sucesso. Ver [[05-entregavel-e-avaliacao#Critérios Críticos|critério d]].

- [ ] Escolhi ferramenta (chatbot / assistente / recomendação) #tarefa/e
- [ ] Justifiquei com dados e ML (mínimo 3 linhas)
- [ ] Conectei à meta `+20% vendas digitais`

> [!TIP] Exemplo extra (critério desejável c)
> Proponha além do mínimo: quiz + chatbot integrado + e-mail personalizado por cluster.

### Tarefa (f) — Registrar prompt(s)

> [!QUOTE] `Atividade_1_...docx:35`
> `f) registrar, no documento de entrega, o(s) prompt(s) utilizado(s) na ferramenta de IA.`

> [!IMPORTANT] Registro faz parte da entrega — `Atividade_1_...docx:16`
> Cole o(s) prompt(s) **na íntegra**, com data/hora e ferramenta usada.

- [ ] Registrei prompt(s) completo(s) em [[templates/registro-prompts|registro-prompts]] #tarefa/f
- [ ] Incluí ferramenta (Gemini/ChatGPT/Copilot) e versão
- [ ] Adicionei ao documento final `entregaveis/`

---

## 🔗 Mapa de Dependências

```mermaid
flowchart TD
    A[(a) Analisar Quadro 2] --> B[(b) Prompt + 2 personas]
    B --> C[(c) Revisar/Corrigir]
    C --> D[(d) Jornada 3 etapas x2]
    D --> E[(e) Ferramenta + ML]
    B & C & E --> F[(f) Registrar prompts]
    F --> G[[05 Entregável]]
```

## 📊 Dataview — Tarefas pendentes desta atividade

```dataview
TASK
FROM "docs/04-tarefas-passo-a-passo"
WHERE !completed
```

---

> [!SUCCESS] Próximo passo
> [[05-entregavel-e-avaliacao|05 — Entregável e Avaliação]] para saber exatamente o que entregar.

#tarefas #passo-a-passo
