# Tariff Impacts on U.S. Microeconomic Outcomes

This repository contains an analysis of the microeconomic effects of U.S. tariffs on strategically important intermediate goods: polysilicon, steel, and aluminum. Using publicly available trade and price data, the project provides descriptive evidence on how tariffs influence import volumes, domestic prices, and downstream market outcomes.

## Project Overview

U.S. trade policy has increasingly relied on tariffs to protect domestic industries, secure supply chains, and influence geopolitical leverage. While tariffs can reduce imports from targeted countries, they often generate complex microeconomic effects, including price increases, import substitution, and downstream cost pass-through.

This analysis focuses on three key intermediate goods:

- Polysilicon – critical input for semiconductors and solar photovoltaics.

- Steel products – widely used in manufacturing and construction.

- Aluminum products – used in industrial and consumer applications.

The objective is to provide policy-relevant, descriptive insights rather than causal elasticity estimates.

## Data Sources

U.S. Census Bureau – Monthly import values by Harmonized System (HS) codes.

Federal Reserve Economic Data (FRED) – Producer Price Index (PPI) series for relevant downstream industries, indexed to January 2018 = 100.

## Selected Products and Codes:

Product: HS Code ;	PPI Proxy (FRED)
Polysilicon:	280461 (HS Code);	PCU334413334413 (Semiconductors) (PPI Proxy (FRED))
Steel:	7208(HS Code);	WPU1017 (Steel Mill Products) (PPI Proxy (FRED))
Aluminum:	7606 HS Code);	WPU10250162 (Extruded Aluminum) (PPI Proxy (FRED))

## Methodology

- The project evaluates tariffs from a microeconomic perspective:

- Quantity response: Monthly import value changes.

- Price response: Domestic PPI changes faced by firms.

- Policy markers: Major tariff announcement or enforcement dates.

## Key expected short-run effects of tariffs include:

- Higher domestic prices

- Reduced imports from targeted countries

- Substitution toward domestic production or alternative foreign suppliers

- Cost pass-through to downstream industries

- The analysis primarily uses visualization of price and quantity responses to illustrate these effects.

## Key Findings
1. Polysilicon

- Observed: Sharp decline in imports after tariffs on Chinese suppliers; semiconductor PPI remains elevated.

- Mechanism: Inelastic demand, limited substitutes, delayed price adjustment.

- Implication: Short-term costs for downstream industries; potential long-term domestic investment benefits.

2. Steel

- Observed: Large import decline following Section 232 tariffs; steel PPI rises significantly.

- Mechanism: Import compression benefits domestic producers, but downstream users face higher costs.

- Implication: Producer gains partially offset by downstream efficiency losses.

3. Aluminum

- Observed: Moderate import decline with partial recovery; moderate PPI increase.

- Mechanism: Supplier substitution and elastic supply allow faster market adjustment.

- Implication: Smaller welfare losses compared to steel; limited long-term insulation for domestic producers.

### Cross-Commodity Comparison
Commodity: Import Response/	Price Response/	Key Mechanism
- Polysilicon:	Sharp decline Sticky/ elevated	Supply chain rigidity
- Steel:	Large decline/	Strong increase/	Domestic market power
- Aluminum:	Moderate decline recovery/ Moderate increase/ 	Supplier substitution

### Policy Implications

- Tariffs on upstream inputs can disproportionately harm downstream industries.

- Gains to domestic producers often come at the expense of broader industrial competitiveness.

- Market structure and supplier substitutability influence the effectiveness and efficiency of tariffs.

- Complementary policies (R&D support, subsidies, supply chain diversification) are necessary to mitigate welfare losses.

### Reproducibility

All data are publicly available:

- U.S. Census Trade Data

- FRED PPI Series

### Future research extensions could include:

- Difference-in-differences estimation with control commodities

- Pass-through elasticity estimation

- Firm-level downstream impact analysis



