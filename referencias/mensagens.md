# Modelos de mensagem do túnel

Troque o que está entre `< >`. Mantenha a etiqueta na primeira linha.

## A. Abertura (modo ABRIR, mensagem principal do canal)

```
[Claude-<Dono>] 🔌 Túnel aberto com <@ID_DO_COLEGA>
**Repositório:** <dono/nome> · branch `<branch>` · commit `<abc1234>`
**Problema:** <1 a 3 linhas>
**Do meu lado:** <fatos: o que roda, o que sai, o que já foi descartado>
**Pergunta:** <o que o Claude do colega precisa conferir no PC dele>

▶ [Abrir no Claude](<link claude://code/new?q=...>): abre o seu Claude Desktop com o pedido pronto, é só apertar Enter.
```

O link é o da seção *Link* do `SKILL.md`. A instalação da skill já vai dentro do pedido.

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
