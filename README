# Desafio LangChain na prática

Esse projeto foi desenvolvido para o desafio LangChain na prática, na pós-graduação em Machine Learning Engineering da FIAP. O desafio consistia na criação de uma cadeia de roteamento (Router Chain) usando o LangChain que receba uma pergunta de um usário, analise a categoria da pergunta e a direcione para o modelo adequado.

A prosposta no projeto que desenvolvi é a criação de uma cadeia de roteamento que auxilie estudantes a direcionarem suas perguntas para uma das três áreas do conhecimento: ciências exatas, ciências humanas e linguagens. 

O próprio modelo usado neste desafio reconhece qual a disciplina referente a pergunta e a responde, se apresentando como um professor da área de conhecimento escolhida.

## Sobre o LangChain

O LangChain é um framework de código aberto criado para facilitar o desenvolvimento de aplicações que se integram com modelos de LLM (Large Language Models), como o Llama e GPT. O LangChain permite o desenvolvimento de sistemas robustos alimentados por esses modelos, de forma simples e eficiente. 

Alguns exemplos de sistemas que podem ser criados com o LangChain são Chatbots, agentes autônomos, sistemas que realizam consultas em documentos de qualquer formato e sistemas de tradução, entre outros.

## Chains e RouterChains

Um dos principais destaques no LangChain é a possibilidade de criar Chains. As Chains vêm da necessidade de quebrar problemas maiores e complexos em problemas menores, quebrando em etapas a serem resolvidas em sequência.  

Isso é possível através do encadeamento de prompts, onde a saída de um prompt é processada pelo modelo e se torna a entrada do próximo processamento, até o resultado final. Isso reduz a complexidade das tarefas e gera uma modularidade, que torna cada etapa reutilizável, com facilidade de manutenção e flexibilidade para integrar diferentes modelos e fontes de dados.

Existem diversos tipos de Chains, e um deles são as Router Chains, que permitem um roteamento dos prompts com base na entrada, possibilitando direcionar problemas ou perguntas diferentes. No caso deste projeto, as router chains foram utilizadas para direcionar perguntas que pertencem a áreas de conhecimento diferentes. Perguntas de ciências exatas, ciências humanas e linguagens são direcionadas para prompts específicos, de acordo com a forma que o modelo as classifica, e são inseridas em diferentes modelos de prompts.
