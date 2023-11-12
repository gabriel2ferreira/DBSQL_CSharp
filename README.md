# Desafio de Projeto: Consultas SQL em Banco de Dados .NET

## Visão Geral do Projeto

Este projeto consiste em um desafio prático que faz parte do módulo de banco de dados da trilha .NET da DIO (Digital Innovation One). O contexto do desafio gira em torno de um banco de dados de um site de filmes, que armazena informações sobre filmes, atores, gêneros, elenco e relacionamentos entre eles.

O objetivo do projeto é realizar consultas SQL no banco de dados, utilizando as tabelas fornecidas, para obter informações específicas sobre filmes, atores e gêneros. As consultas abrangem uma variedade de cenários, desde a simples recuperação de dados até consultas mais complexas que envolvem junções e filtragens.

## Estrutura do Banco de Dados

O banco de dados, chamado "Filmes", é composto por cinco tabelas:

1. **Filmes:** Armazena informações sobre os filmes, como nome, ano e duração.
2. **Atores:** Contém dados sobre os atores, incluindo nome e gênero.
3. **Generos:** Representa os diferentes gêneros dos filmes.
4. **ElencoFilme:** Relaciona atores a filmes, permitindo que um ator participe de vários filmes e um filme tenha vários atores.
5. **FilmesGenero:** Estabelece uma relação muitos para muitos entre filmes e gêneros.

## Como Executar o Projeto

Antes de executar as consultas, é necessário configurar o ambiente:

1. **Banco de Dados:** Execute o script SQL fornecido (`Script Filmes.sql`) no SQL Server para criar o banco de dados e suas tabelas.

2. **Consultas SQL:** Utilize as consultas SQL fornecidas no código SQL para extrair informações específicas do banco de dados.

## Lista de Consultas Realizadas

1. **Busca de Nome e Ano dos Filmes:** Consulta que retorna o nome e o ano de todos os filmes.

2. **Ordenação de Filmes por Ano:** Consulta que retorna o nome e o ano dos filmes, ordenados por ordem crescente pelo ano.

3. **Detalhes do Filme "De Volta para o Futuro":** Consulta que traz o nome, ano e duração do filme "De Volta para o Futuro".

4. **Filmes Lançados em 1997:** Consulta que retorna os nomes dos filmes lançados em 1997.

5. **Filmes Lançados Após 2000:** Consulta que retorna os nomes dos filmes lançados após o ano 2000.

6. **Filmes com Duração Específica:** Consulta que retorna os nomes dos filmes com duração maior que 100 e menor que 150, ordenados pela duração em ordem crescente.

7. **Quantidade de Filmes por Ano:** Consulta que retorna a quantidade de filmes lançados por ano, ordenando pela quantidade em ordem decrescente.

8. **Atores do Gênero Masculino:** Consulta que retorna o primeiro nome e último nome dos atores do gênero masculino.

9. **Atores do Gênero Feminino Ordenados:** Consulta que retorna o primeiro nome e último nome dos atores do gênero feminino, ordenados pelo primeiro nome.

10. **Nome do Filme e Gênero:** Consulta que retorna o nome do filme e o gênero correspondente.

11. **Filmes do Gênero "Mistério":** Consulta que retorna o nome do filme e o gênero para filmes do tipo "Mistério".

12. **Detalhes de Elenco por Filme:** Consulta que traz o nome do filme e detalhes sobre o elenco, incluindo o primeiro nome, último nome e papel dos atores.

## Contribuição

Sinta-se à vontade para contribuir com melhorias ou propor novas consultas para enriquecer o desafio. Faça um fork do repositório, implemente suas alterações e envie um pull request.

Esperamos que este desafio ajude no aprimoramento de habilidades em SQL e no entendimento de consultas em bancos de dados relacionais. Boa prática!
