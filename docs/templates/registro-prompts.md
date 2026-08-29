---
aliases: ["Registro de Prompts", "Log IA"]
tags: [senai, template, prompt, registro, ia, atividade1, obsidian]
cssclass: clean
created: 2026-08-29
updated: 2026-08-29
source: Atividade_1_Aluno_Persona_e_Experiencia_do_Cliente.docx
tipo: template
---

# Template — Registro de Prompts (IA Generativa)

> [!QUOTE] Fonte — `Atividade_1_...docx:35-37`
> `f) registrar, no documento de entrega, o(s) prompt(s) utilizado(s) na ferramenta de IA.`
> `Usar uma ferramenta de Inteligência Artificial generativa (sugestão: Gem personalizado no Gemini, ChatGPT ou Copilot) para ajudar a criar as personas, escrevendo o(s) prompt(s) e registrando-o(s) por completo no documento de entrega.` — `Atividade_1_...docx:37`

> [!IMPORTANT] Sem registro literal = reprova CC-c
> Cole o prompt **na íntegra**. Ver [[05-entregavel-e-avaliacao#Critérios Críticos (elimina se faltar)|CC-c]].

## Prompt 1 — Geração de Personas

| Campo | Valor |
|---|---|
| **Data/Hora** | `2026-08-29 09:45` |
| **Ferramenta** | `Ex: ChatGPT-4o / Gemini Gem / Copilot` |
| **Versão** | `Ex: GPT-4o 2026-08` |
| **Link conversa** | `https://... (se houver)` |
| **Objetivo** | `Gerar 2 personas Grão Vivo` |

### Prompt literal (copiar/colar)

````markdown
COLE AQUI O PROMPT NA ÍNTEGRA — ver [[06-guia-ia-e-prompts#6.3 Modelo de Prompt — Copiar e Colar|modelo 06]]
Ex:
# CONTEXTO DO CLIENTE — Grão Vivo
...
# OBJETIVO DA PERSONA
...
# FORMATO DE SAÍDA
...
````

### Output da IA (resumo ou print)

> [!QUOTE] Output bruto
> Cole aqui o output ou `![[print.png]]` — mantenha evidência.

### Correções aplicadas (CSE2 — senso crítico)

- [ ] Correção 1: `Ex: IA gerou 22 anos capital → corrigi para 34 Registro/SP (Quadro 2: 28-45 região)` #correcao
- [ ] Correção 2: `Ex: IA ignorou ticket R$45 → ajustei renda`
- O que mantive: 
- Limitação da IA observada: `Ex: generalização excessiva`

## Prompt 2 — Jornada do Cliente (opcional, mas recomendado)

| Campo | Valor |
|---|---|
| **Data/Hora** | `2026-08-29 11:15` |
| **Ferramenta** | `Ex: ChatGPT-4o` |
| **Link conversa** | `https://...` |

### Prompt literal

```markdown
COLE AQUI O PROMPT 2 NA ÍNTEGRA — ver [[06-guia-ia-e-prompts#6.4 Segundo Prompt — Jornada (encadeado)|modelo jornada]]
```

### Output / Correções

- Correção: 

## Prompt 3 — Refinamento / Extra (se houver)

| Campo | Valor |
|---|---|
| **Data/Hora** |  |
| **Ferramenta** |  |
| **Prompt** |  |

## Checklist de Registro

- [ ] Prompt(s) na íntegra (não resumido)? #registro
- [ ] Ferramenta + versão + data?
- [ ] Link para conversa (se disponível)?
- [ ] Correções registradas (evidência CSE2)?
- [ ] Copiado para documento final em `entregaveis/`?

> [!TIP] Dataview — auditoria
> ```dataview
> TABLE tags, source
> FROM "docs/templates/registro-prompts"
> ```

---

> [!SUCCESS] Fim do registro
> Agora compile tudo em `entregaveis/EntregaFinal.pdf` e valide com [[07-checklist-e-templates#7.1 Checklist Final — Antes de Entregar|checklist final]].

#template #registro #prompt
