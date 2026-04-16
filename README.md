# toguro

Skill não-oficial pro Claude Code que responde no estilo do influenciador brasileiro [Toguro](https://www.instagram.com/toguro/) — injeta exatamente 1 bordão por resposta mantendo precisão técnica.

> "isso não é skill, é sabor skill" — ninguém

## Pra quem não é dev

Não precisa instalar nada. Abre [PROMPT.md](PROMPT.md), copia o bloco e cola no [Claude](https://claude.ai) — web ou celular. Funciona do mesmo jeito.

## Instalação (Claude Code / devs)

Como é uma skill pessoal (não publicada oficialmente), clona e link pro diretório de skills do Claude Code:

```bash
git clone https://github.com/abensur/toguro ~/projects/toguro
ln -s ~/projects/toguro ~/.claude/skills/toguro
```

Ou copia direto se preferir não usar symlink:

```bash
cp -r toguro ~/.claude/skills/
```

Pronto. A skill aparece nas próximas sessões do Claude Code.

## Uso

Três formas de invocar:

- `/toguro` — invoca explicitamente
- "modo toguro" / "fala igual toguro" — auto-trigger pela descrição
- Em qualquer turno, o modelo pode disparar se o contexto pedir (o Claude decide)

## O que faz

- Responde em português brasileiro.
- Injeta **exatamente 1 bordão** do Toguro por resposta.
- Mantém precisão técnica — nunca distorce informação pro meme funcionar.
- Usa o padrão curinga "sabor X" quando nenhum outro bordão encaixa.

## Bordões catalogados

- **sabor X** — o carro-chefe ("isso não é REST, é sabor REST")
- **calma pai / devagar pai** — pausa e paciência
- **em pleno [ano]** — choque com algo datado
- **choquei, né?** — ironia pós-revelação
- **haverá sinais** — prenúncio de consequência
- **não vai pra BC** — desencoraja escolha ruim

Detalhes e contexto em [`references/bordoes.md`](references/bordoes.md).

## Exemplos

Veja [`examples/before-after.md`](examples/before-after.md) pra comparação resposta normal vs estilo Toguro.

## Verificação

Pra conferir que tá funcionando, roda um dos prompts em `examples/before-after.md` e compara se a resposta bate com o esperado (1 bordão, precisão técnica mantida, português).

## Disclaimer

Projeto feito por brincadeira. Não é afiliado ao Toguro nem à Casa Maromba. Use com responsabilidade — ou não, sabor responsabilidade.

## Licença

[Unlicense](LICENSE) — domínio público. Faz o que quiser.
