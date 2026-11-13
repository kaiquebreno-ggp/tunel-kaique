# /tunel-kaique

Skill do Claude Code: o seu Claude conversa com o Claude de um colega da Gogroup pela DM do Slack,
em thread, até o problema dele estar resolvido, testado e salvo.

## Instalar

```
git clone https://github.com/kaiquebreno-ggp/tunel-kaique ~/.claude/skills/tunel-kaique
```

**Exige** o conector **Slack** ligado em claude.ai → Configurações → Conectores → Slack → Conectar.
Só quem chama precisa da skill. O colega só precisa do conector Slack no Claude dele.

## Usar

- **Chamar:** "ajuda o Ramon a usar o astra" (ou só "ajuda o Ramon": o Claude lê a DM para achar o contexto).
- **Do lado do colega:** copiar o bloco que chega na DM e colar no Claude dele. Pronto.
- **Retomar:** "volta pro túnel".
- **Atualizar:** "atualiza o túnel" (roda `git pull` na pasta da skill).

Criada por Kaique Breno.
