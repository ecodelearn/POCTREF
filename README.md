# 🎯 Framework POCTREF

**Dominando a Engenharia de Prompts com Estrutura e Precisão**

[![License: WTFPL](https://img.shields.io/badge/License-WTFPL-brightgreen.svg)](http://www.wtfpl.net/about/)
[![GitHub stars](https://img.shields.io/github/stars/ecodelearn/POCTREF.svg?style=social&label=Star)](https://github.com/ecodelearn/POCTREF)

---

## 📝 Sobre

No universo da Inteligência Artificial generativa, a qualidade da sua saída está diretamente ligada à qualidade da sua entrada. O **Framework POCTREF** é uma metodologia estruturada para criar prompts eficazes que geram respostas precisas, relevantes e úteis.

## 🚀 O que é POCTREF?

POCTREF é um acrônimo que representa os 6 componentes essenciais para construir prompts de alta qualidade:

| Componente | Descrição |
|------------|-----------|
| **🎭 [P] Persona** | Define quem é o assistente/especialista |
| **🎯 [O] Objetivo** | Estabelece claramente o que deve ser alcançado |
| **📋 [C] Contexto** | Fornece informações de background relevantes |
| **✅ [T] Tarefas** | Lista ações específicas e mensuráveis |
| **⚠️ [R] Regras e Restrições** | Define limitações e diretrizes |
| **💡 [E] Exemplos** | Mostra casos de uso ou padrões esperados |
| **📊 [F] Formato de Saída** | Especifica a estrutura da resposta |

## 🏗️ Estrutura do Framework

### [P] Persona
```
Você é um [ESPECIALISTA/PAPEL], com especialização em [ÁREA DE EXPERTISE]. 
Sua comunicação é [ESTILO DE COMUNICAÇÃO]. Você entende [CONHECIMENTOS ESPECÍFICOS].
```

### [O] Objetivo
```
O objetivo é [AÇÃO PRINCIPAL] e [RESULTADO ESPERADO].
```

### [C] Contexto
```
[Informações relevantes sobre a situação, empresa, projeto, etc.]
```

### [T] Tarefas
```
1. [Tarefa específica 1]
2. [Tarefa específica 2]
3. [Tarefa específica n]
```

### [R] Regras e Restrições
```
- [Regra/limitação 1]
- [Regra/limitação 2]
- [Regra/limitação n]
```

### [E] Exemplos
```
- [Exemplo do que é esperado]
- [Padrão de resposta desejado]
```

### [F] Formato de Saída
```
Use exatamente esta estrutura:
# Título
## Seção 1
[Conteúdo]
## Seção 2
[Conteúdo]
```

## 🎯 Exemplo Prático

Aqui está um exemplo completo de como aplicar o Framework POCTREF:

### Cenário: Análise de Artigo para Newsletter Interna

```markdown
### [P] Persona
Você é um Analista de Estratégia Sênior, com especialização em identificar insights acionáveis para equipes de produto. Sua comunicação é clara, concisa e focada em negócios. Você entende profundamente as dinâmicas do mercado SaaS e gestão de projetos.

### [O] Objetivo
O objetivo é analisar o artigo fornecido, extrair os pontos mais críticos para nossa equipe de produto e apresentá-los de forma clara e digerível para uma newsletter interna.

### [C] Contexto
Nossa empresa desenvolve um software de gestão de projetos (SaaS) para pequenas e médias empresas. O foco principal do nosso produto é melhorar a colaboração e a eficiência das equipes. Estamos sempre buscando tendências que possam influenciar nosso roadmap.

--- INÍCIO DO ARTIGO ---
**Título: A Revolução Silenciosa: Como a IA Preditiva está Remodelando a Gestão de Projetos**
[Conteúdo do artigo...]
--- FIM DO ARTIGO ---

### [T] Tarefas
1. Leia e compreenda completamente o artigo fornecido.
2. Escreva um resumo executivo do artigo em no máximo 3 frases.
3. Identifique os 3 principais insights (key takeaways) do artigo.
4. Para cada insight, escreva um parágrafo de "Impacto para Nós".
5. Sugira uma "Ação Imediata" baseada na sua análise.

### [R] Regras e Restrições
- Use uma linguagem profissional, mas evite jargões excessivamente técnicos.
- Seja objetivo e direto ao ponto.
- **Use apenas a informação contida no artigo.** Não adicione conhecimento externo.
- A resposta final não deve ultrapassar 400 palavras.
- Formate toda a resposta usando Markdown.

### [E] Exemplos
- Um "Impacto para Nós" deve ser algo como: "O artigo menciona a automação de relatórios. Para nós, isso significa que podemos explorar a criação de um dashboard automatizado..."

### [F] Formato de Saída
Use exatamente esta estrutura Markdown:

# Análise do Artigo: [Título]
## Resumo Executivo
[Seu resumo de 3 frases aqui]

## Principais Insights e Impacto
### 1. [Nome do Insight]
**Impacto para Nós:** [Análise]

### 2. [Nome do Insight]
**Impacto para Nós:** [Análise]

### 3. [Nome do Insight]
**Impacto para Nós:** [Análise]

## Ação Imediata Sugerida
[Sua sugestão de ação aqui]
```

## 💡 Benefícios

- ✅ **Consistência**: Resultados mais previsíveis e confiáveis
- ✅ **Clareza**: Comunicação mais eficaz com IAs
- ✅ **Eficiência**: Menos iterações para obter o resultado desejado
- ✅ **Escalabilidade**: Framework reutilizável para diferentes contextos
- ✅ **Qualidade**: Saídas mais estruturadas e úteis

## 🛠️ Como Usar

1. **Identifique seu objetivo**: O que você quer alcançar?
2. **Defina a persona**: Que tipo de especialista você precisa?
3. **Forneça contexto**: Quais informações são relevantes?
4. **Liste as tarefas**: O que especificamente deve ser feito?
5. **Estabeleça regras**: Quais são as limitações e diretrizes?
6. **Dê exemplos**: Como deve ser a saída ideal?
7. **Defina o formato**: Qual a estrutura esperada?

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

- Reportar bugs
- Sugerir melhorias
- Adicionar novos exemplos
- Melhorar a documentação

## 📄 Licença

```
        DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
                    Version 2, December 2004 

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net> 

 Everyone is permitted to copy and distribute verbatim or modified 
 copies of this license document, and changing it is allowed as long 
 as the name is changed. 

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE 
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION 

  0. You just DO WHAT THE FUCK YOU WANT TO.
```

---

**Feito com ❤️ para a comunidade de Engenharia de Prompts**

*Transforme suas interações com IA de frustrantes para fantásticas!*
