# 🌐 Gravity Sessions [Institutional Architecture]

> _Created by H33RNAN | Technical tools & algorithm builder (Python / Pine Script)._

**[🇪🇸 Español]**
La mayoría de los indicadores de sesiones ensucian el gráfico con cajas de colores permanentes. **Gravity Sessions** es un motor dinámico diseñado para BTCUSDT (24/7) que rastrea la liquidez, detecta trampas institucionales y calcula la gravedad del precio respecto a la apertura diaria.

### ⚙️ Core Engineering
1. **True Day Open (TDO) Gravity Oscillator:** El precio es un elástico anclado a la medianoche de NY (00:00 EST). El HUD lateral calcula la distancia del precio al TDO normalizada por volatilidad (Sigma ATR). Si supera 1.5, el HUD alerta `EXTREME` (reversión inminente).
2. **Institutional Ghosting & Sweep Detection:** Las cajas proyectan liquidez. Si una mecha perfora pero no cierra, se marca un **Sweep (✗)**. Si el cuerpo cierra, el nivel se mitiga. Al mitigarse ambos lados, la caja entra en "Ghosting" (Gris oscuro), eliminando el ruido visual.
3. **Contextual EMAs (Visual Amnesia):** EMAs 50/200 activables por menú. Solo se renderizan en las últimas 300 velas, dándote contexto de tendencia en el presente mientras mantienen tu historial inmaculado.
4. **Tonal Families UI:** Agrupación visual por espectro de color (Asia/Fucsia, London/Naranja, NYC/Verde).

---

**[🇬🇧 English]**
Most session indicators clutter the chart with permanent colored boxes. **Gravity Sessions** is a dynamic engine designed for BTCUSDT (24/7) that tracks liquidity, detects institutional traps, and calculates price gravity relative to the daily open.

### ⚙️ Core Engineering
1. **True Day Open (TDO) Gravity Oscillator:** Price is a rubber band anchored to NY Midnight (00:00 EST). The HUD calculates the price distance to TDO normalized by volatility (Sigma ATR). If it exceeds 1.5, the HUD alerts `EXTREME` (mean reversion probable).
2. **Institutional Ghosting & Sweep Detection:** Boxes project liquidity. If a wick pierces but doesn't close, it's marked as a **Sweep (✗)**. If the body closes, the level is mitigated. When both sides are mitigated, the box enters "Ghosting" state (Dark Grey), eliminating visual noise.
3. **Contextual EMAs (Visual Amnesia):** 50/200 EMAs available via menu. Rendered only on the last 300 bars, giving you current trend context while keeping your history pristine.
4. **Tonal Families UI:** Visual grouping by color spectrum (Asia/Fuchsia, London/Orange, NYC/Green).

---

### ⚖️ License & Disclaimer

**License:** GNU Affero General Public License v3.0 (AGPLv3)

⚠️ **RISK DISCLAIMER / EXENCIÓN DE RESPONSABILIDAD**
*Gravity Sessions is a quantitative analysis tool strictly for educational and algorithmic research purposes. It is NOT financial advice. Cryptocurrency trading carries extreme risk of capital loss. The author (H33RNAN) is not responsible for any financial loss, damage, or liquidation incurred by the use, misuse, or interpretation of this code. By using this script, you agree that you are 100% responsible for your own execution decisions.*
