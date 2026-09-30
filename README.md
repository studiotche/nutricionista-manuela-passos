# Nutricionista Nibea Machado — Site Institucional & Conversão

Site institucional moderno, estático, responsivo e de alta performance para a **Nutricionista Nibea Machado** (CRN-2 19127D), com SEO local otimizado para Estância Velha/RS, dados estruturados (Schema.org) e foco em conversão via WhatsApp.

## Stack

- [Astro](https://astro.build/) 6.0
- TypeScript
- Vanilla CSS com design tokens
- Integração `@astrojs/sitemap`

## Imagens & Identidade Visual

As referências e caminhos de imagens em `src/data/site.ts` estão configurados para:

1. `logo`: `/assets/images/logo-nutricionista-nibea-machado.webp` (~320x80px SVG ou WebP com fundo transparente)
2. `hero`: `/assets/images/hero-nibea-machado.webp` (~750x950px vertical)
3. `heroMobile`: `/assets/images/hero-mobile-nibea-machado.webp` (~500x600px vertical)
4. `about`: `/assets/images/sobre-nibea-machado.webp` (~600x750px vertical)
5. `consultorio`: `/assets/images/consultorio-nibea-machado.webp` (~800x600px horizontal)
6. `consultorioFachada`: `/assets/images/fachada-nibea-machado.webp` (~800x600px horizontal)
7. `favicon`: `/assets/images/favicon-nibea-machado.webp` (~128x128px)

Basta adicionar os arquivos com esses nomes na pasta `public/assets/images/` para atualizar as fotos da nutricionista.

## Desenvolvimento Local

```bash
npm install
npm run dev
```

## Build de Produção

```bash
npm run build
```

## Deploy via GitHub Pages

O deploy é automático na branch `main` através do workflow do GitHub Actions em `.github/workflows/astro.yml`.
