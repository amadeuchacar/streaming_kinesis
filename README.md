# Projeto 2 - Engenharia de Dados

Projeto realizado no curso "*Formação Engenharia de Dados: Domine Big Data!*".

## Objetivo 🎯
- 1. Criar um produtor de dados, processar esses dados em streaming no AWS Kinesis Data Stream e criar um consumidor para estes dados.
- 2. Criar um produtor de dados e entregá-lo para o AWS Kinesis Data Firehose, para que este armazene os dados produzidos em um bucket S3.

## Requisitos 📄
- Credenciais de segurança da AWS (chaves de acesso);
- Stream de dados criado no AWS Kinesis Data Stream;
- Entregador de dados AWS Kinesis Data Firehose criado, vinculado a um bucket S3;

## Desenvolvimento 👨🏻‍💻
### 1️⃣ Primeira etapa
O notebook para a criação de um produtor de dados está disponível no arquivo "*produtor.ipynb*", presente neste repositório;

O notebook para a criação de um consumidor de dados está disponível no arquivo "*consumidor1.ipynb*", presente neste repositório;

Processo: O produtor irá produzir dados, irá enviá-lo para o Kinesis Data Stream em formato JSON, e o consumidor irá consumi-lo;

### 2️⃣ Segunda etapa
O notebook para a criação de um produtor de dados está disponível no arquivo "*produtor.ipynb*", presente neste repositório;

O fluxo de entrega no AWS Kinesis Data Firehose deve estar criado e vinculado ao stream de dados do AWS Kinesis Data Stream, na plataforma da AWS, conforme imagem abaixo;

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e562d8d0-0a88-4d49-89b3-bc1f7a08c07d/Untitled.png)

Ao executar o produtor, os dados serão armazenados em um bucket S3 previamente configurado junto ao Firehose, conforme imagem abaixo;

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c0eba8b0-2438-49df-bbd5-4e51949ea25c/Untitled.png)

O arquivo gerado pelo produtor e armazenado no bucket S3 está disponível no arquivo "*KDS-S3-n4hDk-2-2023-02-17-14-38-59-4a82c798-0b21-43db-887a-b8e2bc766ff3*", presente neste repositório.
