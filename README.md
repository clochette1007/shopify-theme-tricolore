# 🇫🇷 Shopify Thème Tricolore

Thème Shopify OS 2.0 aux couleurs du drapeau français.

**Palette :** Bleu `#002395` · Blanc `#FFFFFF` · Rouge `#ED2939`

---

## Installation via Shopify CLI

```bash
npm install -g @shopify/cli @shopify/theme
git clone https://github.com/clochette1007/shopify-theme-tricolore.git
cd shopify-theme-tricolore
shopify theme push --store hmk6y7-mx.myshopify.com
```

## Installation via ZIP

1. Télécharger le repo : **Code → Download ZIP**
2. Shopify Admin → **Boutique en ligne → Thèmes → Ajouter un thème → Téléverser un fichier ZIP**
3. Activer le thème

## Personnalisation des couleurs

Admin → **Boutique en ligne → Thèmes → Personnaliser** → Section « Paramètres du thème » → Couleurs

## Ajout du logo

Admin → **Boutique en ligne → Thèmes → Personnaliser** → Header → Logo (upload image)

## Structure

```
shopify-theme-tricolore/
├── layout/theme.liquid
├── assets/theme.css
├── sections/
│   ├── header.liquid
│   ├── hero-banner.liquid
│   ├── featured-collection.liquid
│   ├── editorial-split.liquid
│   ├── collection-grid.liquid
│   ├── testimonials.liquid
│   ├── newsletter.liquid
│   └── footer.liquid
├── templates/
│   ├── index.json
│   ├── product.json
│   ├── collection.json
│   ├── page.json
│   └── cart.json
├── config/settings_schema.json
└── locales/fr.default.json
```
