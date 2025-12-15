# SilverToken Investment Protocol (SLVT)

SilverToken is a USDT-denominated, silver-referenced digital investment protocol designed to provide transparent exposure to silver price movements without relying on liquidity pools or open market trading.

## Key Characteristics
- Asset-referenced pricing (Silver Spot Price)
- USDT-based settlement
- No AMM or Liquidity Pool
- Internal OTC buy & sell mechanism
- Transparent fee and tax model
- Investment-backed silver acquisition

## How SilverToken Works
SilverToken pricing is derived from global silver spot reference prices.
Each purchase represents an investment position indexed to silver value.

The protocol does not rely on exchange-based price discovery.
All buy and sell operations are executed via a controlled OTC mechanism.

## Silver Backing Model
For every net investment amount:
- Equivalent silver exposure is recorded
- Silver acquisition is executed equal to investment value
- Internal reserve tracking ensures asset coverage per order

SilverToken does not represent direct ownership of physical silver,
but reflects a silver-indexed investment position.

## Pricing Model
- Sell Price: Reference Price (Silver Spot)
- Buy Price: Reference Price minus 3% spread

Displayed prices are indicative and not market-driven.

## Fees
### Buy:
- 1% variable fee
- +1 USDT fixed fee

### Sell:
- 1% variable fee
- +1 USDT fixed fee

## Tax Handling
A 12% tax is applied at redemption time.
Tax is calculated after fees and transferred to a designated tax wallet.

## Smart Contracts
- SilverToken.sol (Token Contract)
- PriceOracle.sol (Pricing Reference)
- InvestmentManager.sol (Execution Logic)

## Disclaimer
SilverToken is a digital investment instrument.
It is not a security, stablecoin, or commodity ownership claim.

Participation involves financial risk and value fluctuation.

## Documentation
- Whitepaper: /whitepaper/SilverToken_Whitepaper_v1.pdf
- Pricing Model: /docs/pricing-model.md
- Fee & Tax Model: /docs/fee-tax-model.md

---
© SilverToken Investment Protocol
