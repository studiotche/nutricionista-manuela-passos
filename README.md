# Nutricionista Manuela B. Passos — Site Institucional & Conversão

Site institucional moderno, estático, responsivo e de alta performance para a **Nutricionista Manuela B. Passos** (CRN-2 18285D), com foco em Nutrição Materno-Infantil, Gestantes e Reeducação Alimentar Familiar, SEO local otimizado para Dois Irmãos/RS e Vale dos Sinos, dados estruturados (Schema.org) e alta conversão via WhatsApp.

## Stack

- [Astro](https://astro.build/) 6.0
- TypeScript
- Vanilla CSS com design tokens e paleta personalizada (Azul Petróleo, Areia Suave, Menta e Caramelo Nude)
- Integração `@astrojs/sitemap`

## Imagens & Identidade Visual

As referências e caminhos de imagens em `src/data/site.ts` estão configurados para:

1. `logo`: `/assets/images/logo-nutricionista-manuela-passos.webp` (~320x80px SVG ou WebP com fundo transparente)
2. `hero`: `/assets/images/hero-manuela-passos.webp` (~750x950px vertical ou 1200x1200px)
3. `heroMobile`: `/assets/images/hero-mobile-manuela-passos.webp` (~500x600px vertical)
4. `about`: `/assets/images/sobre-manuela-passos.webp` (~600x750px vertical)
5. `consultorio`: `/assets/images/consultorio-manuela-passos.webp` (~800x600px horizontal)
6. `consultorioFachada`: `/assets/images/fachada-manuela-passos.webp` (~800x600px horizontal)
7. `favicon`: `/assets/images/favicon-manuela-passos.webp` (~128x128px)

Basta substituir os arquivos com esses nomes na pasta `public/assets/images/` para carregar as fotos definitivas da nutricionista.

## Desenvolvimento Local

```bash
npm install
npm run dev
```

## Build de Produção & Verificação de Tipagem

```bash
npm run check
npm run build
```

## Deploy via GitHub Pages

O deploy é executado via workflow do GitHub Actions em `.github/workflows/astro.yml` quando configurado no repositório.
