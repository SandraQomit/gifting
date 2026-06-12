# Qomit · Tunnel Gifting (ba&sh)

Prototype de tunnel d'achat cadeau (gifting checkout) responsive, en marque **ba&sh**, propulsé par Qomit.

## Lancer
Servir le dossier en HTTP (les polices `@font-face` ne se chargent pas en `file://`) :

```bash
ruby -run -e httpd . -p 8123
# puis ouvrir http://localhost:8123/index.html
```

## Contenu
- `index.html` — tout le tunnel (HTML + CSS + JS inline), responsive (breakpoint 768px)
- `tokens.css` — design tokens Bash (couleurs, typo)
- `fonts.css` + `fonts/` — polices BashTodo (@font-face, base64/otf)
- `images/` — visuels (produit, écrins, cartes, message vidéo, ticket)

Étapes : Mon cadeau (écrin → carte → message → vidéo) · Livraison · Paiement · Confirmation.
