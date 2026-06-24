# Monitoramento e Processamento de Logs com Bash

## Sobre o projeto

Este laboratório tem como objetivo praticar comandos Linux e automação com Bash Script por meio de um script de processamento de arquivos de log.

O script realiza filtragem, tratamento, ordenação, remoção de duplicidades, geração de estatísticas e combinação de logs processados.

## Objetivos praticados

- Localizar arquivos `.log`
- Filtrar mensagens de erro
- Identificar dados sensíveis
- Mascarar informações sensíveis
- Ordenar registros
- Remover duplicidades
- Comparar arquivos
- Gerar estatísticas
- Centralizar logs processados
- Identificar origem dos logs com tags de frontend e backend

## Comandos utilizados

- `find`
- `grep`
- `sed`
- `sort`
- `uniq`
- `diff`
- `wc`
- `echo`
- `basename`
- `mkdir`
- `cat`
- `date`

## Conceitos aplicados

- Redirecionamento com `>` e `>>`
- Variáveis em Bash
- Laços de repetição
- Condicionais `if`, `elif` e `else`
- Organização de arquivos processados
- Boas práticas iniciais de análise de logs

## Estrutura do laboratório

```text
monitoramento-logs/
├── monitoramento-logs.sh
├── log_stats.txt
└── README.md
Aprendizados

Durante este laboratório, pratiquei a construção gradual de um script Bash para automatizar tarefas comuns de análise de logs, reforçando conceitos importantes para infraestrutura, administração Linux e segurança da informação.
