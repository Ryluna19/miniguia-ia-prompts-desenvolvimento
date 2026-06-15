# Miniguia de Estudos: IA e Engenharia de Prompts no Desenvolvimento de Software

## Sobre o projeto

Este repositório foi criado como parte de um desafio prático da DIO, utilizando o NotebookLM como apoio para organizar estudos, comparar fontes e transformar o conteúdo pesquisado em um material de revisão.

O tema escolhido foi **IA e Engenharia de Prompts no Desenvolvimento de Software**, porque é um assunto diretamente ligado à forma como desenvolvedores podem usar inteligência artificial no dia a dia, seja para estudar, escrever código, revisar erros, criar testes ou melhorar documentação.

A ideia principal deste projeto não foi apenas “pedir respostas para a IA”, mas testar diferentes formas de perguntar, comparar os resultados e organizar um miniguia útil para futuras revisões.

---

## Objetivos de estudo

Com este caderno temático, busquei entender melhor:

* Como LLMs podem apoiar o desenvolvimento de software;
* O que é engenharia de prompts e por que ela influencia tanto a qualidade das respostas;
* Quais técnicas de prompt podem ser usadas em programação;
* Quais cuidados são necessários ao usar IA para gerar ou revisar código;
* Como transformar respostas da IA em um material de estudo mais claro e reutilizável.

---

## Como este material foi criado

O material foi construído a partir de um caderno temático no NotebookLM. Primeiro, selecionei fontes abertas sobre IA, LLMs, engenharia de prompts e desenvolvimento de software. Depois, testei diferentes perguntas para comparar os resultados gerados pela IA.

As respostas mais úteis foram salvas, revisadas e reorganizadas neste README em formato de miniguia, com foco em estudo, revisão futura e aplicação prática no desenvolvimento de software.

---

## Fontes utilizadas

As fontes foram selecionadas e adicionadas ao NotebookLM para servir como base do estudo. Entre elas, foram utilizadas referências sobre LLMs, engenharia de prompts, programação assistida por IA e boas práticas de uso de IA no desenvolvimento.

Principais fontes usadas:

1. [Prompt Engineering | OpenAI API](https://developers.openai.com/api/docs/guides/prompt-engineering)
2. [Machine Learning Glossary | Google Developers](https://developers.google.com/machine-learning/glossary)
3. [What Are Large Language Models (LLMs)? | IBM](https://www.ibm.com/think/topics/large-language-models)
4. [AI in Software Development | IBM](https://www.ibm.com/think/topics/ai-in-software-development)
5. [Structured Chain-of-Thought Prompting for Code Generation](https://arxiv.org/abs/2305.06599)

> Observação: durante a montagem do caderno no NotebookLM, outras fontes complementares também foram consultadas para comparar explicações e enriquecer o conteúdo.

---

## Prompts testados e ajustes feitos

Durante o processo, testei prompts mais simples e depois fui ajustando as perguntas para obter respostas mais úteis.

### Primeiro teste

```text
Explique como a IA pode ajudar no desenvolvimento de software.
```

Esse prompt trouxe uma resposta correta, mas ainda muito genérica. A explicação falava sobre produtividade e geração de código, mas não detalhava muito bem como isso se aplicava em etapas específicas do desenvolvimento.

### Ajuste do prompt

```text
Crie um resumo estruturado sobre como IA e engenharia de prompts podem ajudar no desenvolvimento de software, usando apenas as fontes adicionadas.
```

Com esse ajuste, a resposta ficou mais organizada e separada por temas, como geração de código, debugging, testes, documentação e cuidados de segurança.

### Segundo teste

```text
Compare zero-shot, few-shot, role prompting e chain-of-thought.
```

A resposta explicou os conceitos, mas ainda ficou um pouco solta. Para melhorar, pedi uma comparação em tabela.

### Ajuste do prompt

```text
Compare zero-shot, few-shot, role prompting e chain-of-thought em uma tabela simples, mostrando a descrição, uso de exemplos e principal benefício.
```

Esse formato deixou a comparação mais fácil de entender e mais útil para revisão.

---

### Respostas obtidas

A partir dos prompts testados, o NotebookLM retornou respostas mais úteis quando as perguntas incluíam contexto, objetivo claro e formato esperado.

Os principais resultados obtidos foram:

* Um resumo estruturado sobre o uso de IA no ciclo de vida de desenvolvimento de software;
* Uma comparação entre técnicas de prompt, como zero-shot, few-shot, role prompting e chain-of-thought;
* Um glossário com conceitos essenciais sobre IA, LLMs e engenharia de prompts;
* Uma lista de prompts reutilizáveis para estudo, debugging, revisão de código, testes e segurança;
* Uma análise dos principais cuidados ao usar IA para gerar ou revisar código.

---

## Cicatrizes e aprendizados

Durante o uso do NotebookLM, percebi que perguntas muito abertas geravam respostas amplas demais. Quando eu pedia apenas “explique sobre IA no desenvolvimento”, o resultado era correto, mas pouco prático.

As respostas melhoraram quando comecei a:

* Definir melhor o objetivo da pergunta;
* Pedir respostas em tópicos ou tabelas;
* Solicitar exemplos aplicados à programação;
* Separar os temas por etapas, como código, testes, documentação e segurança;
* Pedir limitações e cuidados, não apenas benefícios.

Um ponto importante foi perceber que a IA pode ajudar muito, mas ainda precisa de validação humana. Mesmo quando a resposta parece bem escrita, o código ou a explicação podem conter falhas, bibliotecas inexistentes, práticas inseguras ou informações desatualizadas.

---

# Miniguia de Estudo

## 1. IA no desenvolvimento de software

A inteligência artificial pode apoiar várias etapas do ciclo de vida de desenvolvimento de software. Ela pode ajudar desde o início de um projeto, sugerindo estruturas iniciais, até etapas mais avançadas, como refatoração, geração de testes e análise de segurança.

Na prática, a IA pode ser usada para:

* Gerar trechos de código;
* Explicar códigos difíceis;
* Ajudar na correção de erros;
* Criar testes unitários;
* Sugerir melhorias de refatoração;
* Apoiar a criação de documentação;
* Ajudar na análise de requisitos.

Apesar disso, o código gerado por IA não deve ser aceito automaticamente. Ele precisa ser revisado, testado e adaptado ao contexto real do projeto.

---

## 2. Engenharia de prompts

Engenharia de prompts é a prática de escrever instruções mais claras e estratégicas para obter respostas melhores de modelos de IA.

Um bom prompt normalmente contém:

* O papel que a IA deve assumir;
* O contexto da tarefa;
* O objetivo esperado;
* O formato da resposta;
* Restrições ou cuidados importantes.

Exemplo simples:

```text
Atue como um professor de programação. Explique o erro abaixo de forma simples, mostre a causa provável e sugira uma correção segura.
```

Esse tipo de instrução tende a gerar uma resposta melhor do que apenas escrever:

```text
Corrija esse erro.
```

---

## 3. Técnicas de prompt estudadas

| Técnica          | Como funciona                                                                | Quando usar                                                       |
| ---------------- | ---------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Zero-shot        | O prompt não fornece exemplos, apenas a instrução                            | Quando a tarefa é simples ou direta                               |
| Few-shot         | O prompt fornece exemplos de entrada e saída                                 | Quando é necessário seguir um padrão específico                   |
| Role Prompting   | O modelo recebe um papel, como professor, revisor ou engenheiro de segurança | Quando a resposta precisa ter um foco específico                  |
| Chain-of-Thought | O modelo é orientado a explicar o raciocínio passo a passo                   | Quando a tarefa envolve lógica, análise ou resolução de problemas |

---

## 4. Aplicações práticas na programação

### Geração de código

A IA pode gerar funções, componentes, estruturas iniciais e exemplos de implementação. Isso ajuda principalmente quando o desenvolvedor sabe o que quer construir, mas precisa de apoio para começar.

### Debugging

Ao colar uma mensagem de erro ou stack trace, a IA pode explicar o que está acontecendo e sugerir possíveis causas. Ainda assim, é importante testar a correção e entender o motivo do erro.

### Refatoração

Modelos de IA podem sugerir melhorias de legibilidade, organização e redução de repetição no código. Isso é útil para estudar boas práticas e melhorar projetos pessoais.

### Testes

A IA pode sugerir testes unitários, casos de borda e cenários de erro que o desenvolvedor talvez não tenha considerado.

### Documentação

LLMs podem ajudar a transformar código em explicações, criar READMEs, documentar APIs e resumir alterações em pull requests.

---

## 5. Limitações e cuidados

O uso de IA no desenvolvimento exige atenção. Alguns riscos importantes são:

* A IA pode gerar informações incorretas com aparência convincente;
* Pode sugerir bibliotecas inexistentes ou desatualizadas;
* Pode criar código inseguro;
* Pode ignorar casos de borda;
* Pode não entender todo o contexto de um projeto grande;
* Pode levar o estudante a copiar código sem entender.

Por isso, uma boa prática é tratar toda resposta da IA como um rascunho. O desenvolvedor ainda precisa revisar, testar e entender o que está sendo usado.

---

## Glossário

**IA:** área da computação voltada à criação de sistemas capazes de realizar tarefas que normalmente exigiriam inteligência humana.

**LLM:** modelo de linguagem treinado com grandes volumes de texto, capaz de gerar respostas, explicações e código.

**Prompt:** instrução enviada para a IA.

**Engenharia de Prompts:** prática de escrever prompts melhores para obter respostas mais úteis e precisas.

**Transformer:** arquitetura usada como base em muitos LLMs modernos.

**Alucinação:** quando a IA gera uma informação incorreta, mas apresenta como se fosse verdadeira.

**Zero-shot:** prompt sem exemplos.

**Few-shot:** prompt com exemplos para guiar a resposta.

**Role Prompting:** técnica em que o modelo recebe um papel específico.

**Chain-of-Thought:** técnica que incentiva a explicação passo a passo do raciocínio.

**RAG:** técnica que conecta o modelo a fontes externas para gerar respostas mais baseadas em documentos ou bases confiáveis.

---

## Prompts reutilizáveis

### 1. Prompt para estudar lógica

```text
Você é um professor de programação. Explique a lógica por trás do problema abaixo sem entregar a resposta pronta. Mostre o raciocínio passo a passo e use exemplos simples.
```

### 2. Prompt para entender erros

```text
Explique a mensagem de erro abaixo de forma simples. Mostre a causa provável, como investigar o problema e uma possível correção.
```

### 3. Prompt para revisar código

```text
Atue como um revisor de código. Analise o código abaixo e sugira melhorias de legibilidade, organização e boas práticas, mantendo o mesmo comportamento.
```

### 4. Prompt para criar testes

```text
Crie casos de teste para a função abaixo, incluindo fluxo normal, entradas inválidas e casos de borda. Explique por que cada teste é importante.
```

### 5. Prompt para segurança

```text
Analise o código abaixo com foco em segurança. Verifique riscos como validação de entrada, exposição de dados sensíveis, injeção de SQL e uso inadequado de credenciais.
```

---

## Conclusão

Este projeto mostrou que a IA pode ser uma ferramenta muito útil para quem está aprendendo ou desenvolvendo software, principalmente quando é usada com bons prompts e pensamento crítico.

O maior aprendizado foi perceber que a qualidade da resposta depende muito da qualidade da pergunta. Prompts mais claros, com contexto e formato definido, geram respostas mais úteis.

Ao mesmo tempo, o uso de IA não substitui a revisão humana. Ela pode acelerar estudos, ajudar na escrita de código e melhorar a documentação, mas o desenvolvedor continua responsável por validar, testar e entender o resultado final.
