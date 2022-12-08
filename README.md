# Criação de um banco de dados com Python e Postgresql

Aqui é apresentada uma proposta de banco de dados que engloba desde as etapas iniciais, como a entrevista com os responsáveis pelo negócio e elaboração do modelo lógico, até as fases finais, com a criação das tabelas e seus relacionamentos, inclusive com a carga exemplificativa de algumas delas.

Há quatro arquivos auxiliares neste repositório: 
- Entrevista com o responsável pelo negócio;
- Modelo lógico
- Script SQL para criação das tabelas do banco de dados
- Script Python para criação de dados fictícios para algumas tabelas e posterior carga no banco de dados

A leitura destes complementa o que é apresentado aqui e, também, dá uma visão mais aprofundada da proposta.

# Serviços utilizados

- https://app.brmodeloweb.com/
- shopify.com/br/ferramentas/gerador-nomes-para-empresas/
- Postgresql
- Jupyter Notebook

# Como usar

O ramo de negócio abordado aqui é o das assessorias, que geralmente fornecem terceirização de atendimento ao consumidor para empresas de todos os portes. No caso apresentado, as empresas principais são fictícias, com seus nomes criados com auxílio da plataforma Shopify, bem como os portes de suas operações - a única regra imposta é a proporção de funcionários em cada cargo.

Primeiramente, criou-se resultado para a entrevista fictício, baseado no que é de conhecimento comum sobre esse tipo de instituição, abordando suas estruturas hierárquicas e relacionais com as empresas para as quais fornece seus serviços.

Em seguida, a partir da entrevista, criou-se um modelo lógico das tabelas necessárias para comportar as informações desejadas pela assessoria, com ênfase em evitar a repetição de informações para economia de memória. No referido modelo já é possível visualizar as conexões existentes entre cada tabela.

Como complemento à etapa anterior, desenvolveu-se um script SQL para a criação dessas mesmas tabelas e suas relações e, também, suas restrições para entrada de dados. Assim foi possível definir padrões para as informações inseridas nas tabelas.

Para finalizar, um script Python foi elaborado para a criação de dados fictícios para 3 tabelas de gestão das operações e uma tabela de tempo. As tabelas usadas como exemplo foram escolhidas apenas para exemplificar como funcionaria a carga dos seus dados com utilização da linguagem Python e, também, para apresentar algumas técnicas de manipulação de dados e dataframes. Vale ressaltar que, principalmente, as funçõoes relacionadas à conexão do Python com o próprio banco de dados Postgresql são as mais essenciais, pois permitem o tratamento dos dados inicialmente com o Python e suas ferramentas, o que facilita bastante a utilização por quem tem mais familiaridade com a linguagem.
