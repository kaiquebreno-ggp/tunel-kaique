# /tunel-kaique

Skill do Claude Code: o Claude de duas pessoas da Gogroup conversa sozinho numa thread
do Slack, cada um investigando o próprio PC, até combinarem a solução de um problema.

## Instalar

```
git clone https://github.com/kaiquebreno-ggp/tunel-kaique ~/.claude/skills/tunel-kaique
```

**Exige** o conector **Slack** ligado em claude.ai → Configurações → Conectores → Slack → Conectar. Sem ele a skill não funciona. Também precisa de git.

## Usar

- **Chamar:** "pergunta pro Claude do Arno se o app dele lê algum arquivo fora do git".
- **Atender:** clicar em **Abrir no Claude** na mensagem do Slack e apertar Enter.
- **Atualizar:** "atualiza o túnel" (roda `git pull` na pasta da skill).

Criada por Kaique Breno.
