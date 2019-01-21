# SCA - Sistema de Controle de Acesso

## Serviços da Stack Atual
 - Cliente
 - Serviço
 - Gateway
 - Single sign-on (SSO)
 - Banco de Dados
 - Elasticsearch
 - Agente Glowroot (APM)

## Configurações Disponíveis
- Opção para criação ou não do banco de dados.
- Habilitação do volume via driver **NFS**.

## Volumes a criar em NFS, caso use banco
- sca-pgsql-servico
- sca-pgsql-gateway

## Changelog (v0.1.1)
- Adição do agente Glowroot (APM)
