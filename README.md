# Biolink · Di Biju

Página de link da bio do Instagram [@dibiju.oficial](https://www.instagram.com/dibiju.oficial/).

**Endereço oficial (vai na bio):** https://dibiju.pages.dev

- `public/index.html`: a página. Peças da vitrine, fotos da loja e links (Shopee, Google) ficam no começo do `<script>`.
- `public/fotos/`: fotos da vitrine e da loja (WebP, 720×960 nas peças).
- `public/logo.webp`: o logo.

## Publicar

```sh
# Cloudflare Pages: dibiju.pages.dev (endereço oficial)
npx wrangler@4 pages deploy ./public --project-name dibiju --branch main

# Cloudflare Workers: dibiju.brenoandreati.workers.dev (endereço antigo, mantido igual)
npx wrangler@4 deploy
```
