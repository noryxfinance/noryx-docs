# Getting Started with Noryx

This guide provides a high-level introduction to the Noryx Platform and its core workflow.

Noryx Finance develops quantitative technology for systematic market analysis, risk evaluation and exchange-connected execution.

## 1. Create an Account

Create a Noryx account through the official platform.

Use a secure password and enable any additional account-security features available to you.

## 2. Choose Your Environment

Depending on your plan and platform access, Noryx may provide different environments such as:

- Demo
- Live
- Backtest or analytical views

Each environment should be clearly identified within the platform.

### Demo

Demo functionality allows users to explore platform behavior without exposing real capital.

### Live

Live functionality may interact with supported exchanges using real API-based trading permissions.

Live trading involves real financial risk.

## 3. Connect a Supported Exchange

Where supported, users can connect an external exchange account through API credentials generated directly on the exchange.

Recommended API permissions:

- read account information
- read market information
- place and manage trading orders

Withdrawal permissions should remain disabled whenever they are not required.

Never share exchange API credentials outside official Noryx interfaces.

## 4. Configure Trading Parameters

Depending on available platform features, users may configure parameters such as:

- capital allocation
- capital per trade
- maximum open positions
- execution mode
- strategy access
- exchange connection

Available settings may vary by plan, strategy version and environment.

## 5. Market Analysis

The Noryx Platform processes market information through several analytical layers.

Typical flow:

Market Data  
↓  
Noryx Market Intelligence  
↓  
Noryx Quant Engine  
↓  
Noryx Risk Engine  
↓  
Noryx Execution Layer

## 6. Noryx Market Intelligence

Market Intelligence evaluates the current market environment.

Possible inputs include:

- market structure
- momentum
- volatility
- volume
- market regime
- multi-timeframe alignment

These inputs provide context for the Quant Engine.

## 7. Noryx Quant Engine

The Quant Engine evaluates potential trading conditions systematically.

It may produce analytical outputs such as:

- directional edge
- signal confidence
- trend alignment
- momentum confirmation
- regime compatibility

The engine can also produce no-trade conditions.

## 8. Noryx Risk Engine

Before execution, the Risk Engine evaluates whether the opportunity satisfies predefined risk conditions.

Potential controls may include:

- confidence thresholds
- volatility filters
- position limits
- capital allocation limits
- market-regime constraints
- exposure controls

A valid signal does not automatically require execution.

## 9. Execution

When a trading condition passes both quantitative and risk evaluation, the Execution Layer may submit an order to the connected exchange.

Actual execution remains subject to:

- exchange availability
- liquidity
- slippage
- order requirements
- latency
- API availability

## 10. Analytics

Noryx Analytics may provide visibility into:

- signal history
- executed trades
- performance
- confidence
- P&L
- drawdown
- strategy behavior
- risk events

Live, demo and backtest results should always remain clearly separated.

## 11. System Status

Platform availability can be reviewed through:

https://noryxfinance.com/status

Where available, the status page may provide information about:

- platform availability
- Quant Engine
- market data
- authentication
- exchange connectivity
- API services

## 12. Research

Noryx Research provides educational and quantitative market content.

https://noryxfinance.com/research

Research content is informational and should not be interpreted as financial advice.

## Security Best Practices

Users should:

- use strong passwords
- enable MFA where available
- keep exchange withdrawal permissions disabled
- regularly review API permissions
- revoke unused credentials
- use only official Noryx websites and interfaces
- report suspicious activity

Security enquiries:

security@noryxfinance.com

## Support

For platform support:

support@noryxfinance.com

General enquiries:

hello@noryxfinance.com

## Important Risk Notice

Trading digital assets involves substantial risk and can result in loss of capital.

Quantitative models, automated systems and historical analysis cannot guarantee future results.

Users remain responsible for understanding the risks associated with any trading activity.

## Disclaimer

Noryx Finance provides software and quantitative market technology.

Nothing in this documentation constitutes financial, investment or trading advice.
