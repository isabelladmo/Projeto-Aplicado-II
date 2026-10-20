## Projeto Aplicado II

### Da Transação ao Insight: Estruturação e Análise de Dados de um E-commerce

Este projeto tem como objetivo realizar a estruturação e análise de dados transacionais de uma empresa de comércio eletrônico, utilizando como base o conjunto de dados Online Retail, disponibilizado pelo UCI Machine Learning Repository.

O projeto busca transformar uma base de dados transacional em uma estrutura relacional organizada e normalizada, possibilitando a realização de consultas e análises sobre vendas, produtos, clientes e regiões. A partir dessas informações, serão identificados padrões de vendas e comportamento dos clientes, buscando gerar insights que possam contribuir para a tomada de decisões comerciais.

Os dados utilizados são disponibilizados publicamente pelo UCI Machine Learning Repository.

Fonte oficial dos dados:

UCI Machine Learning Repository — Online Retail

Disponível em:

https://archive.ics.uci.edu/dataset/352/online+retail

Sobre a base de dados

O conjunto de dados contém transações realizadas por uma empresa de varejo eletrônico entre 01/12/2010 e 09/12/2011.

A base possui informações relacionadas a:

Faturas e transações;/
Produtos;/
Quantidades comercializadas;

Preços;

Datas das compras;

Clientes;

Países.

Essas informações serão utilizadas para estruturar um banco de dados relacional e, posteriormente, realizar análises sobre as operações comerciais e o comportamento dos clientes.

### Objetivos do Projeto

1. Analisar e compreender a estrutura da base de dados Online Retail
2. Identificar as principais entidades, atributos e relacionamentos presentes nos dados
3. Normalizar a base e estruturar um banco de dados relacional
4. Criar tabelas relacionadas a clientes, produtos, faturas e itens das faturas
5. Desenvolver consultas SQL para análise das informações
6. Analisar vendas, faturamento, produtos e distribuição geográfica das transações
7. Avaliar o comportamento dos clientes considerando aspectos como recência, frequência e valor das compras
8. Identificar padrões de consumo e possíveis segmentos de clientes com comportamentos semelhantes
9. Gerar insights que possam contribuir para estratégias comerciais e tomada de decisões
10. Documentar e disponibilizar o desenvolvimento do projeto no GitHub

### Organização do Projeto

Para facilitar a organização e a consulta dos arquivos, o projeto está dividido nas seguintes pastas:

data/: armazena os dados utilizados na análise e os arquivos gerados durante o processamento.
notebooks/: contém o notebook com o código desenvolvido para a análise dos dados.
resultados/: reúne gráficos, tabelas e arquivos gerados durante o projeto.
docs/: contém os documentos e relatórios acadêmicos do projeto.

O arquivo requirements.txt apresenta as principais bibliotecas Python utilizadas no desenvolvimento.

### Ferramentas Utilizadas

Python: linguagem utilizada para o desenvolvimento da análise.
Pandas e NumPy: manipulação e preparação dos dados.
Matplotlib e Seaborn: criação de gráficos para visualização dos resultados.
Scikit-learn: aplicação e avaliação do algoritmo de agrupamento de clientes.

### Desenvolvimento do Projeto

As atividades desenvolvidas incluem a exploração e preparação dos dados, a análise do comportamento dos clientes e a aplicação de técnicas de aprendizado de máquina para identificar grupos de clientes com características semelhantes.

Para a análise dos clientes, foi utilizada a metodologia RFM, baseada em três aspectos:

Recência (Recency): há quantos dias o cliente realizou sua última compra.
Frequência (Frequency): quantidade de compras realizadas pelo cliente.
Valor Monetário (Monetary): valor total gasto pelo cliente.

Em seguida, foi utilizado o algoritmo K-Means para agrupar os clientes. Os agrupamentos foram avaliados por meio de métricas como Silhouette Score e Davies-Bouldin, auxiliando na análise da qualidade dos resultados.

### Resultados Esperados

A análise busca identificar diferentes perfis de clientes e gerar informações que possam auxiliar em decisões comerciais, como ações para incentivar novas compras e estratégias de fidelização.

Os resultados apresentados são exploratórios e podem servir como base para análises futuras.

### Como Executar

1. Baixe ou clone este repositório.
2. Instale o Python e as bibliotecas utilizadas no projeto.
3. Abra o notebook disponível na pasta notebooks/.
4. Confira o caminho da base de dados no código.
5. Execute as células do notebook em ordem para reproduzir a análise.

Etapas do Projeto:

[Primeira Etapa - Projeto Aplicado II.pdf](https://github.com/user-attachments/files/31579659/Primeira.Etapa.-.Projeto.Aplicado.II.pdf)

[Segunda Etapa - Projeto Aplicado II.pdf](https://github.com/user-attachments/files/32675725/Segunda.Etapa.-.Projeto.Aplicado.II.pdf)
