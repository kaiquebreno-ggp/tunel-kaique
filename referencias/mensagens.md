# Modelos de mensagem do túnel

Troque o que está entre `< >`. Os blocos A e B vão na DM do dono com o colega, fora de thread.
Tudo que vier depois vai na thread dessa mensagem.

## A. Primeira mensagem COM CONTEXTO (o dono explicou, ou está no histórico da DM)

````
Ei <Colega>, manda isso pro teu Claude 👇 (copia o bloco inteiro e cola no chat dele)

```
Oi, Claude do <Colega>! Aqui é o Claude do <Dono>. Vamos conversar pelo MCP do Slack, na THREAD da mensagem do <Dono> que começa com "Ei <Colega>, manda isso pro teu Claude" (DM <Dono> <-> <Colega>, canal <ID da DM>). Responde sempre nessa thread, começando com [Claude-<Colega>]. Eu leio a cada 1 minuto.

O problema: <o que acontece, em 1 a 2 frases>.
<O que resolve, se você sabe: passos, endereço, NOMES de variável, armadilhas, em lista curta.>

Pra começar, responde na thread:
1. <pergunta>
2. <pergunta>
Depois <teste curto que prova que funciona> e me conta o resultado.

No fim, salva isso no teu CLAUDE.md global/memória pra próxima vez que o <Colega> pedir <assunto>.
<Regra fixa do dono, se houver.>
```
````

## B. Primeira mensagem SEM CONTEXTO (não se sabe ainda qual é o problema)

````
Ei <Colega>, manda isso pro teu Claude 👇 (copia o bloco inteiro e cola no chat dele)

```
Oi, Claude do <Colega>! Aqui é o Claude do <Dono>, ele me pediu pra ajudar vocês. Vamos conversar pelo MCP do Slack, na THREAD da mensagem do <Dono> que começa com "Ei <Colega>, manda isso pro teu Claude" (DM <Dono> <-> <Colega>, canal <ID da DM>). Responde sempre nessa thread, começando com [Claude-<Colega>]. Eu leio a cada 1 minuto.

Primeiro, pergunta ao <Colega> o que está travando e olha o PC dele (só leitura). Depois me responde na thread:
1. o que vocês querem fazer
2. o que acontece (erro ou tela, com a mensagem exata)
3. o que já tentaram e o resultado
4. onde está o projeto e os NOMES das variáveis envolvidas (nunca valor de chave)

Quando resolvermos, salva o aprendizado no teu CLAUDE.md global/memória.
```
````

## C. Fechamento (na thread, só depois do teste que funcionou + confirmação de que salvou)

```
[Claude-<Dono>] Confirmado do meu lado: <teste e resultado>. Última passada: <o que ainda evita o problema voltar | nada mais a acrescentar>. 🔒 Encerrado daqui.
```
