# CryptoDashboard

Dashboard de criptomonedas estilo **CoinMarketCap** con datos en tiempo real. Visualiza precios, rankings, gráficos, indicadores de mercado y más.

## Características

- **Visión General** — Top 10 criptomonedas por capitalización con precios en USD, cambio 24h/7d y sparklines
- **Ranking** — Top 50 criptomonedas con columnas de precio, 1h/24h/7d, capitalización y volumen
- **Vista de Detalle** — Información ampliada de cada criptomoneda al hacer clic
- **Categorías** — L1, L2, DeFi, Meme, RWA y más
- **Ganadores/Perdedores** — Mejor y peor rendimiento en 24h
- **Mercados** — Visión general, exchanges, mercado spot, flujos de exchange
- **Indicadores** — Índice de Miedo y Codicia, temporada de altcoins, dominio de BTC, CMC 20 Index
- **ETF** — Flujos de ETFs de criptomonedas, Bitcoin y Ethereum
- **Derivados** — Liquidaciones (longs/shorts) y tasas de financiación
- **DexScan** — Tokens trending en DEX con datos on-chain
- **Análisis Técnico** — RSI y MACD de las principales criptomonedas
- **Comunidad** — Feed social con publicaciones, tendencias y tópicos
- **Portafolio** — Seguimiento personal de criptomonedas
- **API** — Documentación interactiva de la API de CoinMarketCap
- **Autenticación** — Login con Google One Tap o email/contraseña via Convex
- **Búsqueda** — Filtro en tiempo real por nombre o símbolo

## Tecnologías

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Estilos:** Diseño oscuro con animaciones CSS, diseño responsivo
- **APIs de Datos:**
  - [CoinGecko API](https://www.coingecko.com/en/api) — Precios, market cap, gráficos
  - [DexScreener API](https://docs.dexscreener.com/) — Tokens DEX
  - [Convex](https://www.convex.dev/) — Autenticación de usuarios
- **Autenticación:** Google One Tap (OAuth 2.0) + registro/login propio
- **Iconos:** Assets de CoinGecko y CoinMarketCap
- **Servidor:** Node.js (servidor HTTP estático)

## Cómo ejecutar

```bash
# Servir la aplicación
node server.js
```

Abrir [http://localhost:5500](http://localhost:5500) en el navegador.

## Estructura del proyecto

```
Criptodashboard/
├── index.html      # Aplicación completa (HTML + CSS + JS)
├── server.js       # Servidor HTTP estático (puerto 5500)
├── .gitignore
└── README.md
```

## Captura

Tema oscuro con sidebar de navegación, topbar con búsqueda, tabla principal de criptomonedas con sparklines y múltiples vistas estilo CoinMarketCap.

## Licencia

Uso personal y educativo.
