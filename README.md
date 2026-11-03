# bnvx-site

Mídia pública do Instagram **@iluminuraapp**, servida pelo GitHub Pages em **https://midia.bnvx.com.br**.

O site bnvx.com.br e o backend de assinaturas do Iluminura continuam no Netlify. Aqui ficam apenas os arquivos estáticos que a Instagram Graph API baixa na hora de publicar.

## Estrutura

```
iluminura/social/AAAA-MM/
  stories/AAAA-MM-DD-{bomdia|curio|desafio|noite}.mp4
  posts/AAAA-MM-DD-post.jpg
  reels/AAAA-MM-DD-reel.mp4
```

Exemplo: `https://midia.bnvx.com.br/iluminura/social/2026-11/stories/2026-11-03-bomdia.mp4`

A publicação é feita pelo repositório privado **bnvx/iluminura-social**, que monta a URL com o secret `MEDIA_BASE_URL=https://midia.bnvx.com.br`.

## Mês novo

Suba a pasta `iluminura/social/AAAA-MM/` antes do dia 1. Limites do GitHub Pages: 100 MB por arquivo, ~1 GB por site; apague meses antigos quando passar de ~800 MB.
