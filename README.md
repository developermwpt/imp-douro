# IMP Douro — Property Maintenance & Renovation Website

Website profissional para a **IMP Douro**, empresa de manutenção e renovação de propriedades em Dubai.

## Visão Geral

Site single-page (SPA) desenvolvido em HTML/CSS/JS puro, sem dependências locais. Pronto para deploy em Firebase Hosting, Vercel, Netlify ou qualquer plataforma de hosting estático.

## Estrutura

```
website/
├── public/
│   ├── index.html          # Website completo (single file, ~55KB)
│   ├── logo.png            # Logótipo
│   ├── robots.txt          # Configuração para crawlers
│   ├── sitemap.xml         # Sitemap SEO
│   ├── llms.txt            # LLMs context
│   └── img/                # Imagens das áreas (Dubai Marina, Downtown, etc.)
├── firebase.json           # Configuração Firebase Hosting
└── .firebaserc             # Projeto Firebase
```

## Secções do Site

1. **Header** — navegação sticky com efeito de scroll
2. **Hero** — headline principal com CTAs e estatísticas
3. **Serviços** — 6 cards de serviços (manutenção, pintura, landscaping, etc.)
4. **Porquê nós** — 4 estatísticas + 5 pontos diferenciadores
5. **Sobre** — missão e destaques da empresa
6. **Áreas** — 24 zonas de Dubai cobertas
7. **Pacotes** — 3 tiers (Basic, Standard, Premium)
8. **Contacto** — formulário + dados de contacto
9. **Footer** — links e créditos
10. **WhatsApp Button** — botão flutuante (canto inferior direito)

## Contacto da Empresa

- **Telefone / WhatsApp:** +971 56 464 1047
- **Email:** douroimp@gmail.com
- **Localização:** Dubai, UAE

## Formulário

Submissão via webhook:  
`POST https://n8n.mobiweb.pt/webhook/impdouro-form`

Campos: `name`, `phone`, `service`, `property_type`, `message`

## Deploy — Firebase Hosting

```bash
npm install -g firebase-tools
firebase login
firebase deploy
```

## Tecnologias

- HTML5 / CSS3 / JavaScript (vanilla)
- Tailwind CSS (CDN)
- Font Awesome 6.4.0 (CDN)
- AOS 2.3.1 — animações de scroll (CDN)
- Google Fonts — Poppins + Inter
- Firebase Hosting

## Versão

`1.0` — Production Ready  
Desenvolvido por [Mobiweb](https://mobiweb.ae)
