# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 07 de Outubro de 2024
Empresa: Abstergo Industries
Responsável: Heitor Dutra Bento

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Heitor Dutra Bento. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 (Simple Storage Service)
- Armazenamento escalável e econômico de dados
- O Amazon S3 será utilizado para armazenar documentos de inventário, históricos de pedidos e dados de clientes de forma segura e escalável. A Abstergo poderá aproveitar diferentes classes de armazenamento para otimizar o custo, como o S3 Infrequent Access para dados menos acessados e o S3 Glacier para arquivamento de longo prazo. Isso permite eliminar a necessidade de infraestrutura física local e pagar apenas pelo espaço de armazenamento realmente utilizado, resultando em uma significativa redução de custos.

Etapa 2: 
- Amazon RDS (Relational Database Service)
- Gerenciamento de banco de dados seguro e escalável
- O Amazon RDS será empregado para gerenciar os bancos de dados relacionados ao estoque, ao rastreamento de pedidos e ao sistema de relacionamento com fornecedores. Como um banco de dados gerenciado, o RDS facilita a administração e a manutenção, reduzindo a carga de trabalho da equipe de TI. Com escalabilidade automática e alta disponibilidade, o RDS permite à Abstergo focar na operação sem se preocupar com manutenção de servidores de banco de dados, resultando em menor necessidade de recursos de TI internos e, consequentemente, em uma redução nos custos operacionais.

Etapa 3: 
- AWS Lambda
- Processamento de dados sem servidor (serverless)
- O AWS Lambda será utilizado para automatizar processos como o processamento de pedidos, envio de notificações para clientes e atualização de inventário. Por ser uma solução serverless, a empresa só paga pelo tempo de execução das funções, o que reduz o custo em comparação com a execução de processos em servidores dedicados. Essa abordagem oferece escalabilidade automática, permitindo que as operações se ajustem conforme o volume de demanda aumenta, sem a necessidade de infraestrutura adicional.




## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado beneficiar-se de uma infraestrutura flexível e econômica, eliminando custos com servidores físicos e reduzindo a dependência de uma equipe interna para manutenção e gerenciamento.*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

[AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/)
[Amazon RDS Documentation](https://docs.aws.amazon.com/rds/)
[Amazon S3 (Simple Storage Service) Documentation](https://docs.aws.amazon.com/s3/)

Assinatura do Responsável pelo Projeto:

Heitor Dutra Bento
