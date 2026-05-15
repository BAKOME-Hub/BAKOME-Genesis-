
<p align="center">
  <img src="https://via.placeholder.com/800x400/0a0a0a/00ff88?text=BAKOME+GENESIS+Rust+Terminal" alt="BAKOME GENESIS" width="100%">
</p>

---

## 📖 Description

**🇫🇷 Français**
BAKOME GENESIS est un terminal de trading quantique monolithique écrit en Rust. Il intègre 21 modules avancés : bridge MetaTrader 5, Order Flow avec spoofing/iceberg, Footprint Charts, scanner 28 paires, IA hybride, NLP sentiment, corrélations multi-actifs, algorithme génétique NSGA-II, moteur thinkScript, volatilité implicite avec Sizzle Index, courbes de risque P&L, BackTest 2 Max (cible win rate 85-88%), pricing d'options Black-Scholes avec Greeks, watchlist dynamique, alertes personnalisées, graphiques Renko/Profile, paper trading, filtre news (blocage 45min), moteur Hawkes+Kalman, détecteur distribution/accumulation, et dashboard web. Compilé en moins de 15 Mo, tourne sur un Pixel 4a 5G. Genesis est le début — la suite arrive.

**🇬🇧 English**
BAKOME GENESIS is a monolithic quantum trading terminal written in Rust. It integrates 21 advanced modules: MetaTrader 5 bridge, Order Flow with spoofing/iceberg, Footprint Charts, 28-pair scanner, hybrid AI, NLP sentiment, multi-asset correlations, NSGA-II genetic algorithm, thinkScript engine, implied volatility with Sizzle Index, P&L risk curves, BackTest 2 Max (85-88% win rate target), Black-Scholes options pricing with Greeks, dynamic watchlist, custom alerts, Renko/Profile charts, paper trading, news filter (45min block), Hawkes+Kalman engine, distribution/accumulation detector, and web dashboard. Compiles under 15 MB, runs on a Pixel 4a 5G. Genesis is the beginning — more is coming.

**🇪🇸 Español**
BAKOME GENESIS es un terminal de trading cuántico monolítico escrito en Rust. Integra 21 módulos avanzados: bridge MetaTrader 5, Order Flow con spoofing/iceberg, Footprint Charts, escáner 28 pares, IA híbrida, sentimiento NLP, correlaciones multi-activos, algoritmo genético NSGA-II, motor thinkScript, volatilidad implícita con Sizzle Index, curvas de riesgo P&L, BackTest 2 Max (objetivo win rate 85-88%), pricing de opciones Black-Scholes con Greeks, watchlist dinámica, alertas personalizadas, gráficos Renko/Profile, paper trading, filtro noticias (bloqueo 45min), motor Hawkes+Kalman, detector distribución/acumulación, y dashboard web. Compila en menos de 15 MB, ejecuta en Pixel 4a 5G. Genesis es el comienzo — más está por venir.

---

## ⚡ Modules / Features / Módulos

| Module | Description |
|--------|-------------|
| 🔗 **Bridge Rust ↔ MQL5** | Communication ultra-rapide avec MetaTrader 5 |
| 📊 **Order Flow + DOM** | Delta, déséquilibres, carnet d'ordres temps réel |
| 🕵️ **Détecteur Spoofing** | Fausses murailles d'ordres institutionnelles |
| 🧊 **Détecteur Iceberg** | Ordres cachés des grandes mains |
| 👣 **Footprint Charts** | Volume profile, delta acheteur/vendeur, POC |
| 🔍 **Scanner 28 Paires** | Forex, Crypto, Indices simultanément |
| 🧠 **IA Prédictive Hybride** | Réseau neuronal + signaux de marché |
| 📰 **Sentiment NLP** | Analyse des news et tweets en temps réel |
| 🔗 **Corrélations Multi-Actifs** | XAUUSD vs DXY vs BTC vs SPX |
| 🧬 **Algo Génétique NSGA-II** | Stratégies qui évoluent automatiquement |
| 🧠 **thinkScript Engine** | Parser, compilateur, runtime pour scripts customs |
| 📊 **Volatilité + Sizzle Index** | IV, activité options inhabituelle |
| 📈 **Courbes de Risque P&L** | Profits/pertes visuels, probabilité de profit |
| ⏪ **BackTest 2 Max** | Walk-Forward + Stress Test (85-88% win rate) |
| 🧮 **Options Pricing** | Black-Scholes, Delta, Gamma, Theta, Vega, Rho |
| 📋 **Watchlist Dynamique** | Colonnes custom, prix temps réel |
| 🔔 **Alertes Personnalisées** | Conditions configurables par symbole |
| 🎨 **Graphiques Avancés** | Renko, Volume Profile |
| 🧪 **Paper Trading** | Simulateur complet avec P&L tracking |
| 🔴 **Filtre News** | Blocage trading 45min sur news majeures |
| ⚡ **Hawkes + Kalman** | Modélisation excitation + filtrage prix |
| 🏦 **Détecteur Distribution** | Accumulation/Distribution institutionnelle |
| 💻 **Dashboard Web** | Interface live sur port 8080 |

---

## ⚙️ Quick Install

```bash
git clone https://github.com/BAKOME-Hub/BAKOME-Genesis.git
cd BAKOME-Genesis
cargo build --release
./target/release/bakome_genesis
