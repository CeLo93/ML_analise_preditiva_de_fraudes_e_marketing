# Solução em AWS para Fluxo de Dados em Tempo Real, Armazenamento e Análise de ML
![fluxogramaHier](https://github.com/CeLo93/ML_analise_preditiva_de_fraudes_e_marketing/assets/92175791/62c63da7-ba87-468a-bea1-717e7ebc9926)

Este repositório apresenta uma solução robusta desenvolvida na Amazon Web Services (AWS) para abordar os desafios de receber dados em tempo real, armazenar informações de forma eficiente e aplicar análises avançadas de Machine Learning (ML). Essa solução foi concebida para atender às demandas específicas de um cliente no Setor Financeiro, onde a implantação de um novo aplicativo de dados em produção é o foco principal. A solução inclui a utilização de modelos de predição de ML para detecção de fraudes e segmentação de clientes visando campanhas de marketing direcionadas.

## Sobre o Cenário

Neste contexto, nosso cliente é uma grande empresa do Setor Financeiro que busca lançar um novo aplicativo de dados em produção. A sua tarefa é oferecer uma Solução Técnica que satisfaça os requisitos do cliente e se alinhe à sua arquitetura. O projeto demanda a aplicação de modelos de ciência de dados para identificar possíveis fraudes, bem como segmentar clientes em tempo real para fins de campanhas de marketing.

## Arquitetura da Solução

A solução foi concebida empregando uma combinação de serviços da AWS, proporcionando uma abordagem completa para os desafios enfrentados:

1. **Amazon Kinesis Streams**: Utilizado para receber e processar fluxos de dados em tempo real de diversas fontes. O Kinesis Streams atua como um canal para direcionar os dados.

2. **Amazon Kinesis Firehose**: Responsável pelo gerenciamento do fluxo de dados, realizando a coleta, transformação e carregamento dos dados processados do Kinesis Stream para os destinos desejados.

3. **Amazon S3**: O armazenamento dos dados é realizado no Amazon S3, garantindo escalabilidade, durabilidade e segurança.

4. **Modelos de Predição de ML**: Implementação de modelos de Machine Learning no Amazon SageMaker para a detecção de fraudes e a segmentação de clientes, com o intuito de otimizar as campanhas de marketing.

## Modelo de Predição de ML

O coração dessa solução é a implementação de modelos de predição de Machine Learning para dois cenários-chave:

1. **Detecção de Fraudes**: Um modelo de ML será treinado para analisar padrões nos dados transacionais em tempo real e identificar transações potencialmente fraudulentas. Isso permitirá a detecção precoce e a tomada de medidas para prevenir possíveis fraudes.

2. **Segmentação de Clientes**: Outro modelo será desenvolvido para segmentar os clientes com base em seu comportamento de compra e preferências. Essa segmentação ajudará a personalizar as campanhas de marketing, aumentando a eficácia e o engajamento.

## Features:
1. *Adição de um gerador de valor de transação anômalo. Como quero simular esses dados de transações, adiciono um valor aleatório de transação, como se fosse uma anomalia. Esse valor tem uma chance de 0.5% de ser chamado para valor_transacao. Ou seja, adicionei uma implementação que a cada dado do cliente gerado, tenha essa probabilidade de 0.5% de  ter uma transação maior, no intervalo de 1k ~ 4k.*

## Instruções para Uso

1. Clone este repositório para o seu ambiente de desenvolvimento local.

2. Configure suas credenciais da AWS no ambiente ou utilize o arquivo de configuração.

3. Siga os guias de implementação fornecidos na pasta "guides" para configurar e implantar cada componente da solução.

4. Personalize os modelos de predição de ML de acordo com as necessidades específicas do seu cenário e prepare os dados de treinamento.

5. Documente os resultados e a performance da solução, destacando como os modelos de predição estão contribuindo para a identificação de fraudes e para a segmentação de clientes de forma mais eficaz.

## Contribuição

Contribuições, sugestões e relatórios de problemas são bem-vindos! Se você identificar algum problema ou tiver ideias para melhorias, sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença
...
