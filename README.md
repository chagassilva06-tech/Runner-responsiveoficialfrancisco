# Francisco Runner

Copia estatica do site publico em https://francisco-app.base44.app/.

## O que esta nesta pasta

- `index.html`: pagina principal.
- `404.html`: fallback para GitHub Pages em rotas de SPA.
- `assets/`: JavaScript e CSS compilados do app.
- `media/`: imagens baixadas do CDN publico da Base44.
- `manifest.json`: manifesto ajustado para caminhos relativos.
- `.nojekyll`: evita processamento do GitHub Pages.

## Publicar no GitHub Pages

1. Crie um repositorio novo no GitHub.
2. Envie todos os arquivos desta pasta para o repositorio.
3. No GitHub, abra `Settings` > `Pages`.
4. Em `Build and deployment`, escolha `Deploy from a branch`.
5. Selecione a branch `main` e a pasta `/root`.
6. Salve e aguarde o GitHub publicar o site.

## Observacao

Esta pasta contem o build estatico recuperado do site publicado. Ela nao e o projeto-fonte original do Base44, entao os arquivos React originais, componentes separados e configuracoes internas do construtor nao estao disponiveis aqui.
