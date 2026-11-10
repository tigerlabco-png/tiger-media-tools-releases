# Tiger Media Tools — instaladores

Este repositório guarda **apenas** os instaladores (`.dmg`) e o manifesto de atualizações do Tiger Media Tools
(Speed Batch, Smart Frame e Camera Ingest). Não há código-fonte aqui.

- `tiger-media-tools.json`: manifesto de atualizações (esquema 2), **assinado** com a chave da Tiger. O app
  Tiger Media Tools recusa qualquer manifesto editado ou assinado por outra chave.
- Releases: um por versão de cada produto (por exemplo `speedbatch-v2.1.0`), com o `.dmg` anexado. O app confere
  o `sha256` de cada arquivo antes de instalar.

Os aplicativos só funcionam com uma licença válida da conta Tiger Media Tools.
