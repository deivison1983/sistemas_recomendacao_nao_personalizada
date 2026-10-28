# Recomendação Não Personalizada: Rankings

## Visão geral
Este notebook explora fundamentos de sistemas de recomendação, com foco em estratégias não personalizadas que podem gerar sugestões mesmo quando a plataforma ainda não conhece as preferências individuais de uma pessoa.

A prática utiliza exemplos de recomendação de filmes com o conjunto de dados **MovieLens**.

## Objetivos

O objetivo é principal **consolidar os fundamentos de sistemas de recomendação** por meio da implementação, do zero e com bibliotecas, de estratégias de **recomendação não personalizada** — aquelas que não dependem do histórico individual do usuário e são essenciais para resolver o problema de **cold start**, quando o sistema ainda não conhece o perfil de quem chega.

## Abordagens exploradas

### Rankings de filmes
Com dados do MovieLens, o notebook realiza análise exploratória das avaliações e constrói listas Top-10 utilizando diferentes critérios:
- **Popularidade:** quantidade de avaliações recebidas por filme.
- **Avaliação média:** ordenação pela nota média observada.
- **Filtro mínimo de votos:** redução do efeito de filmes com poucas avaliações.
- **Classificação ponderada (IMDb Weighted Rating):** combinação da nota média do filme com o número de votos e a média global, equilibrando qualidade observada e volume de avaliações.

A prática evidencia que ordenar apenas pela média pode favorecer filmes com poucas avaliações. A classificação ponderada busca tornar o ranking mais robusto, sem eliminar a necessidade de escolher critérios adequados ao contexto.

## Tecnologias e ferramentas
- Python
- Jupyter Notebook
- Pandas e NumPy para manipulação e análise de dados
- Matplotlib para visualização
- Bibliotecas de mineração de itens frequentes e regras de associação
- Dataset MovieLens (na parte de rankings de filmes)

## Principais aprendizados
- Diferença entre popularidade, nota média e classificação ponderada.
- Impacto do volume de avaliações na ordenação de itens.
- Construção de recomendações baseadas em regras, com critérios de ordenação interpretáveis.

## Autor

Deivison Morais. Visite o meu portfólio de projetos [aqui.](https://deivison1983.github.io/portfolio_projetos/)

Pós-Graduação em Inteligência Artificial e Aprendizado de Máquina - PUC Minas

Professor Orientador: Humberto Mossri

### Contatos

<div>
  <a href = "https://www.linkedin.com/in/deivisonmorais/"><img src = "https://img.shields.io/badge/-deivisonmorais-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href = "mailto:deivison1983@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</div>
