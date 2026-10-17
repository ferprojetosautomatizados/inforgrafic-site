# Instruções para o Lovable

Este projeto é uma captura estática da página **Marketing Contábil com Relacionamento | Plataforma InforGrafic**.

- `index.html` é o ponto de entrada (Vite serve direto).
- `styles.css` contém todos os estilos mesclados.
- `assets/images` e `assets/fonts` contêm as mídias (compartilhadas entre todas as páginas).
- `pages/<slug>/index.html` contém as demais páginas capturadas do site.
- Os `<script>` originais foram preservados no final do `<body>` (com `src` absolutos para CDN). Isso mantém animações JS como GSAP/Lottie funcionando quando possível.

## Páginas capturadas
- `index.html` — https://inforgrafic.com.br/
- `pages/quem-somos/index.html` — https://inforgrafic.com.br/quem-somos/
- `pages/assinaturas/index.html` — https://inforgrafic.com.br/assinaturas/
- `pages/assinaturas-aplicativo-contabil/index.html` — https://inforgrafic.com.br/assinaturas/aplicativo-contabil/
- `pages/assinaturas-blog-contabil/index.html` — https://inforgrafic.com.br/assinaturas/blog-contabil/
- `pages/assinaturas-informativo-contabil-impresso/index.html` — https://inforgrafic.com.br/assinaturas/informativo-contabil-impresso/
- `pages/assinaturas-informativo-digital-contabil/index.html` — https://inforgrafic.com.br/assinaturas/informativo-digital-contabil/
- `pages/assinaturas-link-na-bio/index.html` — https://inforgrafic.com.br/assinaturas/link-na-bio/
- `pages/assinaturas-newsletter-contabil/index.html` — https://inforgrafic.com.br/assinaturas/newsletter-contabil/
- `pages/assinaturas-site-one-page/index.html` — https://inforgrafic.com.br/assinaturas/site-one-page/
- `pages/faq/index.html` — https://inforgrafic.com.br/faq/
- `pages/blog/index.html` — https://inforgrafic.com.br/blog/
- `pages/contato/index.html` — https://inforgrafic.com.br/contato/
- `pages/dependencia-de-indicacao-contabil/index.html` — https://inforgrafic.com.br/dependencia-de-indicacao-contabil/
- `pages/falta-de-comunicacao-na-contabilidade/index.html` — https://inforgrafic.com.br/falta-de-comunicacao-na-contabilidade/

## Bibliotecas de animação detectadas
- (nenhuma biblioteca de animação JS detectada)

## O que você pode pedir ao Lovable
- Converter este HTML/CSS estático em React + Tailwind + Framer Motion / GSAP.
- Transformar cada arquivo em `pages/` em uma rota React (React Router / TanStack Router).
- Recriar as animações detectadas acima como componentes React.
- Ajustar cores, tipografia ou copy mantendo o layout e as animações.
