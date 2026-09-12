# Methodology

## 1. Research Objective

This project evaluates the residential real estate market in Abuja, Nigeria, with the objective of identifying locations and residential segments that may offer attractive opportunities for investors and property developers in 2026.

The analysis considers:

- Market demand
- Residential property prices
- Rental-market conditions
- Gross rental yields
- Price-growth signals
- Infrastructure
- Development potential
- Entry affordability
- Macroeconomic conditions

---

## 2. Data Sources

The analysis uses a combination of:

- Nigeria Property Centre market and demand data
- Central Bank of Nigeria monetary and foreign-exchange data
- National Bureau of Statistics macroeconomic data
- Federal Capital Territory Administration infrastructure and planning information

The source register is maintained separately in:

`sources/sources.md`

---

## 3. Data Classification

Every major data point is classified as one of the following:

### Observed

A figure reported directly by the source.

Examples:

- Median asking price
- Search share
- Number of listings
- Reported gross rental yield
- Inflation rate
- Monetary Policy Rate

### Derived

A calculation performed from observed data.

Example:

Annual rental income estimated from:

`Property Price × Gross Rental Yield`

### Assumption

A value introduced for scenario analysis rather than observed directly in the market.

Examples:

- Operating-cost assumption
- Vacancy assumption
- Future appreciation scenario
- Investment holding period

Observed data must not be presented as an assumption, and assumptions must not be presented as observed market facts.

---

## 4. Property Price Analysis

The primary property-price metric is the median asking price.

Asking prices are not treated as completed transaction prices.

Where bedroom-specific data is available, the analysis prioritizes:

- 2-bedroom properties
- 3-bedroom properties
- 4-bedroom properties

This allows more meaningful comparisons between purchase prices and rental income.

---

## 5. Rental Yield Analysis

Gross rental yield is calculated as:

`Annual Gross Rent ÷ Property Purchase Price × 100`

Where the source provides a reported gross yield, the reported value is retained as the primary observation.

The analysis does not automatically treat gross yield as net investment return.

Operating expenses, vacancy, maintenance, management and other costs must be considered separately.

---

## 6. Location Intelligence

Abuja locations are evaluated using several dimensions:

### Demand

Measured primarily through property-search activity.

### Rental Strength

Measured through rental-search activity and rental-market indicators.

### Price Growth

Year-on-year asking-price movement where available.

### Infrastructure

Presence and significance of relevant infrastructure projects and connectivity improvements.

### Development Potential

Indicators include:

- Land-search demand
- Joint-venture interest
- Development activity
- Infrastructure expansion
- Availability of growth corridors

### Affordability

Relative entry cost compared with other Abuja locations.

---

## 7. Investment Attractiveness Index

A preliminary composite index is constructed using the following weights:

| Factor | Weight |
|---|---:|
| Current Demand | 25% |
| Rental-Market Strength | 20% |
| Price-Growth Signal | 15% |
| Infrastructure | 15% |
| Development Potential | 15% |
| Entry Affordability | 10% |
| **Total** | **100%** |

Each location receives a score from 1 to 10 for each factor.

The weighted score is calculated as:

`Composite Score = Σ(Factor Score × Factor Weight)`

The index is a research framework and should be recalibrated as additional evidence becomes available.

---

## 8. Investor vs Developer Analysis

The project separates two investment perspectives.

### Residential Investor

Focuses on:

- Existing property
- Rental income
- Capital appreciation
- Liquidity
- Entry cost
- Tenant demand

### Property Developer

Focuses on:

- Land acquisition
- Development potential
- Construction economics
- Joint ventures
- Infrastructure
- Target-market demand
- Potential development margin

A location that is attractive to a developer may not necessarily be the best location for a buy-to-let investor.

---

## 9. Investment Scenario Model

Illustrative investment scenarios are created for:

- ₦100 million
- ₦200 million
- ₦500 million

The base model assumes:

- Equity/cash investment
- 20% of gross rental income allocated to operating costs and vacancy
- Five-year holding period

Capital appreciation is tested under three scenarios:

| Scenario | Annual Appreciation |
|---|---:|
| Conservative | 5% |
| Base | 10% |
| Upside | 15% |

These are analytical assumptions, not forecasts.

---

## 10. Limitations

The analysis has several limitations:

1. Listing prices represent asking prices rather than verified transaction prices.
2. Search activity is a demand proxy and does not necessarily represent completed purchases or rentals.
3. Some location-level samples are relatively small.
4. Infrastructure projects may change in timing, scope or completion status.
5. Rental yields can vary significantly by building quality, furnishing, service charges and exact location.
6. Investment scenarios do not constitute financial advice.
7. Actual investment returns will depend on acquisition price, financing, taxes, vacancy, maintenance and exit price.

---

## 11. Research Integrity

The project deliberately distinguishes between:

**What the market data says**

and

**What the analyst assumes.**

All major conclusions should be traceable to either:

1. an observed source;
2. a documented calculation; or
3. an explicitly stated assumption.
