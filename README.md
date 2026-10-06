# Landing Pages

Índice público de landing pages em produção e cases em desenvolvimento.

Este repositório é uma **capa de portfólio**: documenta stack, status, entregas e sites ao vivo. O código de cada projeto fica em repositórios privados quando aplicável.

## Resumo

| Projeto | Stack | Status | Última alteração | Site |
|---------|-------|--------|------------------|------|
| Bioelectric | HTML5, CSS3, JavaScript | Planejamento | 06/10/2026 | — |
| Luiggi Auto | Next.js 15, TypeScript, Tailwind, PostgreSQL, Docker | Produção | 09/09/2026 | [luiggiauto.com.br](https://www.luiggiauto.com.br) |
| Decod Sistemas | HTML5, CSS3, JavaScript (sem framework) | Produção | 28/05/2026 | [decodsistemas.com.br](https://decodsistemas.com.br) |
| Sushi Taito | Next.js, TypeScript, Tailwind CSS, PostgreSQL | Em desenvolvimento | 05/10/2026 | [sushitaito.com.br](https://sushitaito.com.br) |

## Cases

### Luiggi Auto

![Preview Luiggi Auto](docs/previews/luiggiauto.png)

Landing page administrável para o Grupo Luiggi (centro automotivo e guinchos), com painel para edição de conteúdo em produção.

- **Stack:** Next.js 15, React 19, TypeScript, Tailwind CSS, PostgreSQL, CKEditor, GSAP, Docker / Traefik
- **Entrega:** landing + CMS admin, SEO (sitemap/robots), upload de mídia, preview ao vivo, deploy em VPS
- **Destaques técnicos:** autenticação de admin, headers de segurança e CSP, sanitização de HTML, otimização de imagens
- **Repositório:** `lMazer/lp-luiggiauto.com.br` *(privado)*
- **Site:** [https://www.luiggiauto.com.br](https://www.luiggiauto.com.br)

### Decod Sistemas

![Preview Decod Sistemas](docs/previews/decodsistemas.png)

Site institucional multi-página para apresentar a empresa, o produto iCode+, serviços e canais de contato comercial.

> Preview gerado a partir da versão no repositório GitHub. O site público ainda aguarda autorização do cliente para publicação desta versão.

- **Stack:** HTML5, CSS3, JavaScript puro, assets locais (sem build / sem framework)
- **Entrega:** home, produtos, serviços e contato, com CTA via WhatsApp
- **Destaques técnicos:** implementação fiel ao Figma, zero dependências externas de JS, base leve e fácil de manter
- **Repositório:** `lMazer/lp-decodsistemas.com.br` *(privado)*
- **Site:** [https://decodsistemas.com.br](https://decodsistemas.com.br)

### Sushi Taito

| Antes — site atual | Depois — em desenvolvimento |
|:---:|:---:|
| ![Sushi Taito antes](docs/previews/sushitaito-antes.png) | **A nova versão ainda não está pronta.** A prévia “depois” será adicionada após a modernização. |

Modernização da presença digital do restaurante. A imagem à esquerda registra o site atual; o trabalho da nova versão está em desenvolvimento.

- **Stack planejada:** Next.js, TypeScript, Tailwind CSS, PostgreSQL
- **Entrega planejada:** site com painel administrativo, cardápio flipbook, preços configuráveis, integração iFood e gestão manual de avaliações com link para o Google
- **Destaques técnicos planejados:** persistência PostgreSQL, gestão de conteúdo pelo painel, backups próprios documentados
- **Repositório:** `lMazer/lp-sushitaito.com.br` *(privado)*
- **Site:** [https://sushitaito.com.br](https://sushitaito.com.br) *(versão atual; a modernização ainda não foi publicada)*

### Bioelectric

![Preview Bioelectric](docs/previews/bioelectric.png)

Landing page para apresentar a locação de carros elétricos da Bioelectric, com modelos da frota, vantagens da locação e contato por WhatsApp.

- **Stack:** HTML5, CSS3 e JavaScript puro
- **Entrega:** página responsiva com apresentação da frota, benefícios, vídeos e chamadas para contato
- **Destaques técnicos:** layout desktop e mobile, assets locais e galeria de seis vídeos
- **Repositório:** `lMazer/lp-bioelectric.com.br` *(privado)*
- **Site:** — *(sem URL; em planejamento)*

## Padrões que sigo

- Layout responsivo (mobile → desktop)
- SEO básico (títulos, meta, sitemap/robots quando aplicável)
- Performance de assets (imagens otimizadas, peso consciente)
- Acessibilidade mínima (semântica HTML, contraste, navegação por teclado onde faz sentido)
- Documentação e caminho de deploy claros em cada projeto

## Como adicionar um novo projeto

Siga o template em [docs/ADDING_A_PROJECT.md](docs/ADDING_A_PROJECT.md).
