# Modelos de mensagem do túnel

Troque o que está entre `< >`. Mantenha a etiqueta na primeira linha.

## A. Abertura (modo ABRIR) — enxuta, é o que o colega vê

Só uma linha de assunto e o link. Nada de requisito, instalação ou explicação:
a skill cuida disso do lado de lá.

```
[Claude-<Dono>] 🔌 <@ID_DO_COLEGA>, meu Claude quer falar com o seu sobre <assunto em poucas palavras>.
▶ [Abrir no Claude](<link claude://code/new?q=...>)
```

## A2-precisa. Problema detalhado — de quem tem o problema

Primeira mensagem de quem precisa: dentro da thread logo após a abertura (se abriu) ou
como primeira resposta (se atendeu um A2-sabe). É para o outro Claude, não para o colega.

```
[Claude-<Dono>] **Papel:** precisa de ajuda
**Repositório:** <dono/nome> · branch `<branch>` · commit `<abc1234>` (ou "nenhum")
**O que acontece:** <erro, tela ou comportamento, com a mensagem exata se houver>
**Já tentei e não deu:** <cada tentativa e o resultado>
**Pedido:** o que funcionou aí para <assunto>? Onde você vê mais chance de resolver?
```

## A2-sabe. Oferta de ajuda — de quem já resolveu

Primeira mensagem dentro da thread quando quem abriu é quem sabe.

```
[Claude-<Dono>] **Papel:** já resolvi isso aqui e quero ajudar
**O que funcionou aqui:** <passos validados, configuração, regra de negócio; com prova>
**Para eu ajudar:** responde primeiro com o problema detalhado: o que acontece (erro ou tela), o que já foi tentado e não deu certo.
```

## B. Entrada de quem sabe (modo ATENDER, depois de um A2-precisa)

```
[Claude-<Dono>] Entrei. **Papel:** já resolvi algo parecido.
**O que funcionou aqui:** <passos validados, com o comando ou o arquivo que prova>
**Primeiro passo para você:** <uma ação, a de maior chance>
```

## C. Resposta comum (os dois lados)

Quem sabe: o que já funcionou ou foi validado, com prova. Quem precisa: o resultado do
que testou e a próxima pergunta ("o que funcionou aí?", "o que você teve que resolver nisso?").

```
[Claude-<Dono>] <o que encontrei ou testei, com o comando ou o arquivo que prova>
<pergunta de volta, se houver; uma por vez>
```

## F. Nada mais a acrescentar (antes do acordo)

Só depois de quem precisa confirmar que funcionou (teste no PC ou "sim" do dono).

```
[Claude-<Dono>] Confirmado do meu lado: <teste e resultado | dono confirmou>. Última passada: <o que ainda vale passar | nada mais a acrescentar>.
```

## D. Acordo

Só depois de: funcionou do lado de quem precisa + os dois lados escreveram o modelo F.

```
[Claude-<Dono>] ACORDO: <causa em 1 frase>. Solução: <o que cada lado fez>. Confirmado por: <teste ou dono>.
```

## E. Parada sem acordo

```
[Claude-<Dono>] Parando aqui (<20 trocas sem resolver | 15 min sem resposta>). <@ID_DO_DONO> <@ID_DO_COLEGA>, onde travou: <1 frase>.
🔒 Túnel encerrado
```
