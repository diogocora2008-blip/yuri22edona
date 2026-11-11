# Y22 × D19 — Digital Archive

Site responsivo sobre a trajetória pública de Yuri22 e Dona19, feito com HTML, CSS, JavaScript e Bootstrap 5.

## Estrutura

```text
yuri22_dona19_site/
├── index.html
├── yuri22.html
├── dona19.html
├── README.md
└── assets/
    ├── css/style.css
    ├── js/main.js
    └── img/
```

## Como abrir

1. Baixe ou extraia a pasta.
2. Abra `index.html` no navegador.
3. Para publicar, envie todos os arquivos mantendo a estrutura de pastas.

## Como colocar fotos dos criadores

Por respeito a direitos autorais e para evitar usar imagens erradas, o projeto não copia fotos do Instagram ou TikTok. Para adicionar imagens que você tenha autorização para usar:

- Salve uma foto autorizada de Yuri como `assets/img/yuri.jpg`.
- Salve uma foto autorizada de Dona como `assets/img/dona.jpg`.

Os blocos de imagem atuais são fundos gráficos com as iniciais. Para trocar por fotos, edite o CSS:
- `.visual-yuri` e `.image-yuri` para Yuri.
- `.visual-dona` e `.image-dona` para Dona.

Exemplo de CSS para usar a foto:
```css
.visual-yuri, .image-yuri {
  background: linear-gradient(0deg, rgba(0,0,0,.25), rgba(0,0,0,.25)),
              url("../img/yuri.jpg") center/cover no-repeat;
}
.visual-dona, .image-dona {
  background: linear-gradient(0deg, rgba(0,0,0,.25), rgba(0,0,0,.25)),
              url("../img/dona.jpg") center/cover no-repeat;
}
```
Observação: em `index.html`, as classes `.image-yuri` e `.image-dona` já existem; nas páginas individuais, `.visual-yuri` e `.visual-dona`.

## Publicar no GitHub Pages

1. Crie um repositório público no GitHub, por exemplo `yuri22-dona19`.
2. Envie `index.html`, `yuri22.html`, `dona19.html`, `README.md` e a pasta `assets`.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`, depois clique em **Save**.
6. Aguarde a publicação. O endereço ficará parecido com `https://SEU-USUARIO.github.io/yuri22-dona19/`.

## Fontes consultadas

- TaDa Gaming, matéria sobre a parceria com Yuri22, 16/12/2025: https://tadagaming.com/pt-BR/news/content/316
- Games Magazine Brasil, trajetória de Yuri22: https://www.gamesbras.com/apostas-online/igaming/2025/12/17/como-tada-yuri22-construiram-uma-parceria-de-sucesso-no-brasil-por-que-isso-importa-61084.html
- Perfil biográfico de Yuri22: https://pt.wikipedia.org/wiki/Yuri22
- Histórico do canal Dona na Twitch: https://www.betterbanned.com/streamer/dona
- Dados do canal Dona: https://streamersbase.com.br/streamers/dona
- Perfil público de creator Dona19: https://app.getshake.me/c/dona19__

## Nota editorial

A linha do tempo não inventa um acontecimento para cada ano. Quando as fontes consultadas não sustentam uma data ou conquista específica, isso é informado no texto. Seguidores, audiência e status de plataformas podem mudar e não devem ser tratados como números permanentes. Informações pessoais privadas não foram incluídas.
