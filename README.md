# Black-Scholes Option Pricing Calculator

A single-page web app that calculates option prices and Greeks using the Black-Scholes model.

## Features

- **Call & Put pricing** with notional support
- **Greeks**: Delta, Theta, Vega, Gamma
- **Interactive charts** for each Greek vs. price movement with hover tooltips
- Real-time updates as inputs change

## Usage

Open `black-scholes.html` in any browser. No dependencies or build step required.

## Inputs

| Parameter | Description |
|-----------|-------------|
| Current Price | Spot price of the underlying asset |
| Strike Price | Option strike price |
| Time to Expiration | Days until expiry |
| Risk-Free Rate | Annual risk-free interest rate (%) |
| Volatility | Annual volatility (%) |
| Notional | Number of tokens/contracts |
