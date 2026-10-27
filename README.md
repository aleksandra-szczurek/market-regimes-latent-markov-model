# Market Regimes across Crypto, Gold and Volatility: a Latent Markov Model

**Group project** – Statistical Computing Methods, University of Perugia (Oct 2025 – Jan 2026)

## Question

Are there hidden **market regimes** linking traditional and digital assets?

## Data

Monthly returns of Bitcoin, Ethereum, gold (GLD) and the VIX, 2016–2024.

## Method

- **Latent Markov Model** (an extension of Hidden Markov Models to continuous responses) estimated with the `LMest` package
- Model comparison with **AIC and BIC**, with and without the VIX
- Decoding of the latent states over time

## Results

- **3 regimes** identified: stability, crypto growth, and short phases of strong divergence across assets
- The regimes stay **identical with or without the VIX**, pointing to a robust market structure
- **BIC favours the model with the VIX** (AIC slightly prefers the simpler model), suggesting that equity-market fear helps define the regimes
- Gold is almost **uncorrelated with cryptocurrencies**, confirming its role as a diversifier

## Contents

- `report.pdf` – full report with code, tables and figures

## Tools

R · LMest · ggplot2
