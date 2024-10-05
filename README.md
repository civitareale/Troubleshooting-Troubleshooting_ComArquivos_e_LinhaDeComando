# Guia Prático de Ferramentas de Linha de Comando para Investigação de Problemas com logs e outros arquivos
## Introdução
No mundo da tecnologia, a linha de comando é uma aliada poderosa na resolução de problemas técnicos, e na minha opinião muitas vezes as mais rápidas alternativas disponíveis. Ferramentas como `grep`, `awk`, `sed`, `jq`, `sort`, `wc`, entre outras, permitem analisar rapidamente arquivos e logs em busca de possíveis causas de problemas. Este tutorial objetiva:

1. Listar as ferramentas mais relevantes para investigação de problemas.
2. Explicar de forma simples o objetivo principal de cada uma das ferramentas.
3. Apresentar casos práticos com exemplos. Os exemplos utilizam os arquivos que constam na pasta /arquivos desse repo, a fim de facilitar entendimento.

<sub>A ideia por trás da criação desse tutorial não é cobrir todas as possibilidades, mas iniciar um Repo que - com contribuições de todos - talvez se torne algo útil a uma parcela importante de SysAdmins ou pessoas de desenvolviomento</sub>

#TUTORIAL
## 1. Ferramentas Mais Relevantes para Investigação de Problemas
<details>
<summary>
    grep
</summary>
  
  O commando `grep` é utilizado para buscar padrões de texto em arquivos
  ```Shell
  grep "ERROR" application.log
  ```
  Explicação: Procura todas as linhas que contêm a palavra "ERROR" no arquivo application.log.
  Saída:
  ```Shell
  2024-09-28 10:05:00 ERROR Falha ao conectar ao banco de dados
  2024-09-28 10:15:00 ERROR Falha ao reconectar ao banco de dados
  ```
</details>

awk
sed
jq
sort
uniq
wc
cut
head
tail
less
cat
tr
find
xargs

