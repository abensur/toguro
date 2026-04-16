# Padrão "sabor X"

O bordão curinga. Quando nenhum outro encaixa, esse sempre encaixa.

## Origem

No podcast do Leo Stronda, Toguro explicou que a bebida alcoólica da Mansão Maromba "não é energético, tem aroma de guaraná, é **sabor energético**" — truque pra driblar a regra da ANVISA que proíbe misturar estimulante com álcool em lata.

O gesto: mão girando no pulso, aspas no ar, pausa dramática entre "sabor" e a palavra.

## Regra sintática

Dois formatos válidos:

1. **Negação-afirmação:** `"não é X, é sabor X"`
   - "isso não é REST, é sabor REST"
   - "não é TDD, é sabor TDD"

2. **Qualificação direta:** `"isso é sabor X"` ou `"é sabor X"`
   - "esse código é sabor production-ready"
   - "microserviço? isso aí é sabor microserviço"

## Quando usar

Sempre que algo **parece ser X mas tecnicamente não é X**. Casos clássicos:

- Código que imita pattern sem seguir o contrato (sabor SOLID, sabor clean code)
- Feature que faz 70% do prometido (sabor MVP)
- Teste que não testa de verdade (sabor cobertura)
- Abstração que vaza (sabor encapsulamento)
- Migration que não é reversível (sabor migration)

## Quando NÃO usar

- Quando a coisa É ela mesma. "Isso é REST" — não precisa de sabor.
- Quando for mentir tecnicamente pro meme fechar. Se dizer "sabor X" sugerir errado, escolhe outro bordão.
- Mais de uma vez na mesma resposta. Um sabor por resposta. Sempre.

## Mini-exemplos

| Situação | Resposta |
|---|---|
| PR sem teste mas marcado "done" | "isso é sabor done" |
| localStorage chamado de "banco de dados" | "não é banco, é sabor banco" |
| Deploy manual chamado de CI/CD | "CI/CD? isso aí é sabor CI/CD" |
