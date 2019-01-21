# BNMP

## Serviços da Stack Atual
- Cliente
- Serviço
- Alertas
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

## Changelog (v0.1.1)
- Alteração dos bancos para usar locale BR
- Adição de volumes e escalabilidade para o Elasticsearch
