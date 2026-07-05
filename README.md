# projeto-data-engineer

Este projeto foi criado para estudar os fundamentos técnicos e práticos da engenharia de dados, reunindo exemplos de ingestão, enriquecimento e refinamento de dados em um fluxo inspirado na arquitetura medalhão. A proposta é praticar conceitos essenciais de pipelines de dados usando Python, SQL, DuckDB e notebooks, organizando os arquivos de entrada, transformação e persistência de forma clara e versionável.

## Objetivo do estudo

O objetivo principal é compreender como as ferramentas de engenharia de dados se conectam em um processo completo: receber dados brutos, estruturar as etapas de tratamento, aplicar transformações, consultar os resultados e documentar a evolução do projeto. O repositório também serve como base para exercitar boas práticas de organização, controle de versão e uso colaborativo de Git e GitHub.

## Fundamentos trabalhados

- Ingestão de dados a partir de arquivos CSV armazenados na camada `landing`.
- Manipulação e transformação de dados com Python em notebooks.
- Uso de SQL para explorar, consultar e validar informações.
- Persistência local com DuckDB para simular uma base analítica leve e portátil.
- Organização em etapas de processamento, passando por ingestão, enriquecimento e refinamento.
- Aplicação da arquitetura medalhão como referência conceitual para separar dados brutos, tratados e prontos para análise.
- Documentação do projeto para facilitar manutenção, reprodução e aprendizado contínuo.

## Estrutura do projeto

```text
projeto-data-engineer/
├── landing/
│   ├── z0019_1.csv
│   └── z0019_2.csv
├── scripts/
│   ├── ingestao.ipynb
│   ├── enriquecimento.ipynb
│   ├── refinamento.ipynb
│   └── dados_duckdb.db
├── .gitignore
└── README.md
```

## Git e GitHub

O projeto também inclui a prática de Git e GitHub como parte dos fundamentos técnicos. O Git é utilizado para registrar o histórico de alterações, acompanhar a evolução dos notebooks e manter o projeto organizado em commits. O GitHub pode ser usado para armazenar o repositório remoto, compartilhar o estudo, revisar alterações e criar um histórico público ou privado do desenvolvimento.

Como o arquivo `dados_duckdb.db` é um banco local gerado durante a execução dos notebooks, ele foi adicionado ao `.gitignore`. Dessa forma, o repositório evita versionar arquivos binários ou bases locais que podem crescer, mudar com frequência e ser recriadas a partir dos dados e scripts do projeto.

## Tecnologias utilizadas

- Python
- SQL
- DuckDB
- Jupyter Notebook
- Git
- GitHub

## Fluxo de aprendizado

1. Armazenar arquivos brutos na pasta `landing`.
2. Executar a etapa de ingestão para carregar e organizar os dados iniciais.
3. Aplicar enriquecimentos e transformações conforme as regras de negócio ou análise.
4. Refinar os dados para consultas analíticas.
5. Validar os resultados com SQL.
6. Registrar a evolução do trabalho com commits no Git.
7. Publicar ou sincronizar o repositório no GitHub quando necessário.

Este repositório representa um ambiente de prática para consolidar a base técnica necessária em engenharia de dados, combinando conceitos de arquitetura, processamento, armazenamento, versionamento e documentação.
