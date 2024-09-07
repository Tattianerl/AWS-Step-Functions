# AWS Step Functions e AWS Bedrock - Orquestração e IA na AWS

## Visão Geral

Este projeto visa demonstrar o uso do AWS Step Functions para orquestrar múltiplos serviços da AWS em fluxos de trabalho automatizados, além de integrar o AWS Bedrock, uma plataforma de IA generativa que facilita a criação de soluções baseadas em inteligência artificial.

## O que são AWS Step Functions?

O AWS Step Functions é um serviço baseado em máquinas de estado que coordena vários serviços da AWS e código customizado. Ele permite construir fluxos de trabalho, onde cada passo pode ser um serviço AWS ou uma função personalizada, como uma chamada à Lambda.

### Principais Características:
- Orquestração de Serviços: Conecta e gerencia serviços como Lambda, EC2, DynamoDB, S3, entre outros.
- Tolerância a Falhas: Automaticamente tenta novamente tarefas que falham e suporta configurações avançadas de retries.
- Diagrama Visual: Fornece uma visualização clara do fluxo de execução.
- Definição via ASL (Amazon States Language): Os fluxos de trabalho são definidos usando JSON, facilitando a customização.
- Execução Condicional e Paralela: Permite a criação de ramificações no fluxo de acordo com condições predefinidas e a execução de tarefas simultâneas.

## O que é AWS Bedrock?
O AWS Bedrock é uma plataforma que oferece acesso a modelos de IA generativa pré-treinados, sem a necessidade de gerenciar a infraestrutura subjacente. Ele facilita o uso de modelos de linguagem e modelos de geração de conteúdo, integrando-se a serviços da AWS para criar soluções de IA escaláveis.

## Características do AWS Bedrock:
- Modelos Pré-Treinados: Acesso a uma variedade de modelos para geração de texto, imagens e outros.
- Facilidade de Uso: Reduz a complexidade do desenvolvimento de IA, oferecendo APIs fáceis de usar.
- Integração com AWS Services: Trabalha em conjunto com Lambda, S3, Step Functions e outros serviços AWS para uma solução integrada.
- Escalabilidade: Suporte para cargas de trabalho intensivas em IA sem a necessidade de provisionar ou gerenciar servidores.

## Por que usar AWS Step Functions e AWS Bedrock?
- Automatização e Orquestração: AWS Step Functions permite coordenar diferentes serviços AWS em um único fluxo de trabalho.
- Integração com IA: Com o AWS Bedrock, é possível incorporar inteligência artificial em diferentes etapas do fluxo, como geração automática de texto ou imagens.
- Escalabilidade e Tolerância a Falhas: Ambos os serviços oferecem escalabilidade automática e alta resiliência para garantir que as tarefas sejam concluídas com sucesso.

## Como usar:
1. AWS Step Functions: Defina seu fluxo de trabalho em ASL (Amazon States Language) e conecte serviços da AWS como Lambda, DynamoDB e Bedrock.
2. AWS Bedrock: Integre modelos de IA generativa para criar textos ou outros conteúdos automaticamente.
3. Monitoramento e Escalabilidade: Monitore o fluxo de trabalho usando a visualização gráfica do Step Functions e aproveite a escalabilidade do Bedrock para cargas de trabalho intensivas de IA.

# Links Úteis
[AWS Step Functions:]https://aws.amazon.com/pt/step-functions/
[Serverless e Amazon Bedrock:] https://aws.amazon.com/pt/blogs/aws-brasil/como-criar-um-assistente-virtual-de-baixa-latencia-com-multiplos-modelos-usando-serverless-e-amazon-bedrock/

 
