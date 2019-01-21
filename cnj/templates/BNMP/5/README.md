# BNMP

## Serviços da Stack Atual
- Cliente
- Serviço
- Alertas
- Batch
- Sincronização
- Gateway
- Gateway Externo
- Elasticsearch
- Banco para Serviço (opcional)
- Banco para Gateway (opcional)
- Agente Glowroot (APM)

## Configurações Disponíveis
- Habilitação do volume via driver **NFS**.
- Habilitação de criação dos bancos de dados.

## Volumes a criar em NFS, caso use banco
- bnmp-pgsql-servico
- bnmp-pgsql-gateway

## Changelog (v0.1.2)
- Adição do bnmp-batch e bnmp-sincronizacao
