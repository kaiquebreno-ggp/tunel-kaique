# Modelos de mensagem do túnel

Troque o que está entre `< >`. Mantenha a etiqueta na primeira linha.

## A. Abertura (modo ABRIR) — enxuta, é o que o colega vê

Só uma linha de assunto e o link. Nada de requisito, instalação ou explicação:
a skill cuida disso do lado de lá.

```
[Claude-<Dono>] 🔌 <@ID_DO_COLEGA>, meu Claude quer falar com o seu sobre <assunto em poucas palavras>.
▶ [Abrir no Claude](<link claude://code/new?q=...>)
```

## A2. Detalhes (modo ABRIR) — primeira resposta DENTRO da thread da abertura

É para o outro Claude, não para o colega.

```
[Claude-<Dono>] **Repositório:** <dono/nome> · branch `<branch>` · commit `<abc1234>`
**Problema:** <1 a 3 linhas>
**Do meu lado:** <fatos: o que roda, o que sai, o que já foi descartado>
**Pergunta:** <o que o Claude do colega precisa conferir no PC dele>
```

## B. Entrada (modo ATENDER, primeira resposta na thread)

```
[Claude-<Dono>] Entrei. Repositório aqui: branch `<branch>` · commit `<abc1234>`. Conferindo agora.
```

## C. Resposta comum (os dois lados)

```
[Claude-<Dono>] <o que encontrei, com o comando ou o arquivo que prova>
<pergunta de volta, se houver; uma por vez>
```

## D. Acordo

```
[Claude-<Dono>] ACORDO: <causa em 1 frase>. Solução: <o que cada lado faz>.
```

## E. Parada sem acordo

```
[Claude-<Dono>] Parando aqui (<10 trocas sem acordo | 15 min sem resposta>). <@ID_DO_DONO> <@ID_DO_COLEGA>, onde travou: <1 frase>.
🔒 Túnel encerrado
```
