# Pipeline ETL com Python e GPT-4 (Santander Dev Week 2023 / 2025)

Pipeline ETL com Python e IA generativa (GPT-4).

Este projeto é uma adaptação do desafio proposto no Santander Dev Week 2023 com simulações de extração de um API já fora do ar, nele se implementa um pipeline ETL (Extração, Transformação e Carregamento) completo usando Python, organizado no Google Colab. O objetivo é extrair dados de usuários, transformar esses dados gerando mensagens de marketing personalizadas com a API OpenAI GPT-4, e simular o carregamento das mensagens em um sistema de destino, seguindo a proposta do desafio Santander Dev Week 2023.

O projeto demonstra:
* Extração de dados 
* Integração com APIs
* Uso de IA generativa para transformação de dados
* Visualizações e análises exploratórias
* Boas práticas de engenharia de dados
Este pipeline foi adaptado para manter sua essência e lógica mesmo com limitação de API ou recursos externos.

## Principais Tecnologias
Este projeto combina ferramentas de ciência de dados, processamento de informação e IA generativa:

Tecnologia -	Propósito
**Python** -	Linguagem principal para desenvolvimento do pipeline ETL e análises
**Pandas** -	Biblioteca para manipulação e transformação de dados
**Google Colab** -	Ambiente de desenvolvimento executável em nuvem
**OpenAI GPT-4** -	Modelo de linguagem para geração de mensagens personalizadas via API
**Matplotlib / Seaborn** -	Bibliotecas para criação de gráficos e visualizações
**API Mock (simulada)** -	Substitui API externa quando indisponível, mantendo o fluxo
**Estrutura de Prompting** -	Constrói mensagens efetivas para o modelo GPT-4
A integração com GPT-4 exemplifica o uso de grandes modelos de linguagem em pipelines de dados reais.

## IMPORTANTE

Este projeto foi construído com um viés totalmente educacional para a DIO. Por isso, disponibilizamos uma versão mais robusta dele no repositório oficial da DIO:

### [digitalinnovationone/santander-dev-week-2023-api](https://github.com/digitalinnovationone/santander-dev-week-2023-api)

Lá incluímos todas os endpoints de CRUD, além de aplicar boas práticas (uso de DTOs e refinamento na documentação da OpenAPI). Sendo assim, caso queira um desafio/referência mais completa é só acessar 👊🤩
