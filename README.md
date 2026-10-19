# Guitar Game CCB

Jogo estilo Guitar Hero com a biblioteca de **480 hinos**, usando as mesmas versões do Violão Bounce.

## Versões de cada hino
Na tela inicial, escolha a versão e toque no hino:

- 🎼 **Soprano**: só a melodia.
- 🎸 **Soprano + Baixo**: melodia e baixo.
- 🎶 **Soprano + Acomp.**: melodia com acompanhamento em dedilhado.

O tom já vem ajustado para ficar nas primeiras casas (ex.: hino 1 de Mi♭ para Sol maior) e aparece abaixo do nome do hino durante o jogo. A busca aceita número ou título.

## Arquivos
- `hinos/index.json`: lista de hinos (número e título).
- `hinos/NNN.json`: as 3 versões do hino, com corda e casa de cada nota (carregado na hora de jogar).
- Também dá para carregar um MIDI próprio pelo botão da tela inicial.

## Publicação
- Suba **todos** os arquivos e a pasta `hinos` no GitHub (o workflow do APK copia a pasta para dentro do app).
- A cada versão nova, mude `CACHE_NAME` em `sw.js`.
