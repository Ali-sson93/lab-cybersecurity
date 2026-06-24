# Monitoramento e processamento de logs

## Descrição
Laboratório prático desenvolvido em Bash para processar arquivos de log, filtrar eventos relevantes, remover duplicidades, gerar estatísticas e consolidar logs em um arquivo final organizado.

Este projeto foi construído como parte dos meus estudos em Linux e automação, com foco em manipulação de arquivos, uso de comandos nativos do sistema e criação de scripts para tarefas administrativas.

## Objetivo do laboratório
Automatizar o tratamento de arquivos de log, aplicando operações comuns em ambientes Linux, como:

- localizar arquivos de log
- filtrar eventos específicos
- ocultar informações sensíveis
- ordenar e remover registros duplicados
- contar linhas e palavras
- gerar arquivos de estatísticas
- consolidar múltiplos logs em um único arquivo
- identificar se o log é de frontend ou backend

## Funcionalidades implementadas
- Busca de arquivos de log com `find`
- Filtragem de linhas com `grep`
- Anonimização/substituição de conteúdo com `sed`
- Ordenação de eventos com `sort`
- Remoção de duplicados com `uniq`
- Geração de métricas com `wc`
- Extração de nome de arquivo com `basename`
- Criação automática de diretórios com `mkdir -p`
- Consolidação de logs processados em um arquivo final
- Inclusão de tags como `[FRONTEND]` e `[BACKEND]`
- Ordenação final dos logs combinados por data

## Estrutura do laboratório
```bash
linux/monitoramento-logs/
├── monitoramento-logs.sh
├── log_stats.txt
└── README.md
