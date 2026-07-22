# Via Nexa Dashboard — Chile Social Listening

Dashboard interativo de social listening do mercado brasileiro sobre destinos em Chile.
Base: 5.416 menciones capturadas em TikTok e Instagram entre jul/2025 e jul/2026,
11 destinos canônicos, sentimento via LeIA (léxico PT-BR).

## Stack

- HTML/CSS/JS self-contained (single file)
- Chart.js 4.4 via CDN
- Dados agregados embutidos no HTML (~140KB total)

## Publicar

O arquivo `index.html` é standalone. Serve estático em qualquer host:

- **Netlify:** conectar este repo e fazer deploy — o Netlify serve o `index.html` da raiz automaticamente
- **GitHub Pages:** ativar em Settings → Pages → deploy from branch `main` / root
- **Local:** abrir `index.html` no navegador

## Estrutura

```
.
├── index.html          # Dashboard completo (data embutida)
├── netlify.toml        # Config Netlify (opcional)
└── README.md
```

## Cliente

Estudio encomendado por Terena Tamai (Via Nexa Consulting) para
presentación en Connect Latinoamérica — julio 2026.
