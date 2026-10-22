<p align="center">
  <img src="polygraph-mark.svg" width="72" height="72" alt="Polygraph logo">
</p>

<h1 align="center">polygraph</h1>

<p align="center"><b>A research project developing trading strategies for prediction markets.</b></p>

<p align="center">
  Finding potential information advantages. Turning market signals into testable trading strategies.<br>
  <sub>Machine learning · Market data · Strategy evaluation &nbsp;|&nbsp; 🟢 In development / Paper simulations</sub>
</p>

<p align="center">
  <a href="#01--about">About</a> ·
  <a href="#02--research--development">Research &amp; development</a> ·
  <a href="#03--development-status">Development status</a>
</p>

---

## 01 / About

### From information to a trading hypothesis.

**Polygraph is a research project that develops prediction-market trading strategies using machine learning to investigate potential information advantages and test their value through paper simulations.**

Market participants differ in what they know, how they interpret it and how quickly they act. The project studies asymmetric information: whether observable trading activity and market responses reveal signals that prices have yet to fully reflect.

Using market and onchain data from prediction markets such as Polymarket, it investigates pricing discrepancies and translates candidate signals into rules for when to enter, which side to take, how much simulated capital to allocate and when to exit.

The project's research goal is positive risk-adjusted returns after costs. Strategies must be evaluated on later, unseen data and through paper simulations; profitability remains to be demonstrated.

---

## 02 / Research & development

### A signal is a starting point.

The work is turning an observation into a strategy that can withstand careful evaluation.

| | Area | Description |
|---|---|---|
| 01 | **Market data & features** | Build time-aware datasets from prediction-market prices, order books and onchain activity. Study how information moves through markets and which observable patterns may carry a signal. |
| 02 | **Predictive modeling** | Use machine learning to estimate outcomes and short-horizon price changes. Compare model estimates with market prices to identify potential opportunities after trading costs. |
| 03 | **Trading strategy development** | Translate candidate signals into explicit rules for entry, position sizing and exit. Account for signal strength, liquidity and risk limits—including when to abstain from a trade. |
| 04 | **Paper simulation** | Evaluate strategies with simulated capital, incorporating assumptions about fees, liquidity and execution. Examine net returns, drawdowns and sensitivity to those assumptions. |
| 05 | **Asymmetric information** | Investigate whether trading timing, order flow and price responses reveal potential information advantages. Observable patterns are candidate signals; they do not establish what a participant knows or guarantee profitable trades. |

---

## 03 / Development status

### Build. Simulate. Refine.

`● Active development`

**Current work focuses on data quality, predictive models and strategy evaluation through paper simulations.**

The aim is a reproducible assessment of whether candidate strategies remain useful after costs and risk.

<sub>Current evaluation uses simulated capital, not live-money trading.</sub>

---

<p align="center">
  <sub>polygraph — a prediction-market trading research project · <a href="#">Back to top ↑</a></sub>
</p>

<p align="center">
  <sub>Credits: website originally built with ChatGPT; adapted into this README by Claude (Anthropic).</sub>
</p>
