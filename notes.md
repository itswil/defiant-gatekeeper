# 📈 Full Course on Stock Investing - Notes

> Source: [YouTube Video](https://youtu.be/GCzjetZZU54) | Compilation of multiple lectures on stock investing fundamentals

---

## 💰 1. PE Ratio (Price to Earnings)

[Watch Section](https://youtu.be/GCzjetZZU54?t=100)

- **Definition**: Market Cap ÷ Net Income = PE Ratio
- Example: Company with $100B market cap and $10B net income = 10x PE
- PE ratio shows **how long it takes** for a company to earn back the money you paid

### Why PE Ratio is Important

[Watch](https://youtu.be/GCzjetZZU54?t=177)

- PE ratio represents the time needed for the company's earnings to equal your investment
- Example: 10x PE = 10 years to recoup your investment through company earnings
- As a shareholder, you own a % of net income (via dividends or share buybacks)
- Lower PE might seem better (5 years > 10 years), but that's not always the case

### PE from Financial Projections Perspective

[Watch](https://youtu.be/GCzjetZZU54?t=258)

- A 5x PE company is NOT always better than a 10x PE company
- **Future earnings growth matters more than current PE**
- Example: Company A (10x PE, flat earnings) vs Company B (20x PE, growing earnings)
  - Company A: $1B earnings flat for 5 years = $5B total
  - Company B: $500M → $1B → $2B → $3B → $4B = $10.5B total
- Investing in Company B (higher PE) turned out better due to growth
- **Key takeaway**: Company's future prospect > historical performance

### PE from Regression Analysis Perspective

[Watch](https://youtu.be/GCzjetZZU54?t=358)

- Low PE is NOT always good
- Use **regression analysis** to understand PE vs earnings growth relationship
- Formula: y = a + xb (linear regression)
- How to do it in Excel:
  1. Gather 10+ companies in the **same industry**
  2. Plot PE ratio vs next 5 years EPS growth
  3. Create scatter chart with trend line
  4. Add **R² (R-squared)** value
- **R² > 0.8** = strong correlation between PE and earnings growth
- R² ranges from 0 to 1; higher = more confidence in PE valuation

### Always Use Forward PE Ratio

[Watch](https://youtu.be/GCzjetZZU54?t=499)

- Don't use trailing PE (last 4 quarters reported)
- Use **forward-looking PE** based on projected earnings
- Reason 1: Reported earnings have one-off items (taxes, expenses)
- Reason 2: Equity investors are forward-looking (care about future, not past)
- Near year-end, use next year's projected earnings

### Don't Only Rely on PE Ratio

[Watch](https://youtu.be/GCzjetZZU54?t=559)

- PE can be very volatile due to one-off events
- Examples of distortions: political push, geopolitical tension, natural disasters (COVID-19), sudden capital inflows
- Always make your own **hard cold projections**
- Follow your instinct when purchasing

### PE Ratio Summary

[Watch](https://youtu.be/GCzjetZZU54?t=599)

1. PE shows time to recoup investment
2. Future net income forecast determines PE level
3. Verify PE-to-earnings-growth relationship using regression & R²
4. Always use **forward PE**
5. Don't only rely on PE (one-off events can distort)

---

## 🏢 2. EV/EBITDA Multiple

[Watch Section](https://youtu.be/GCzjetZZU54?t=657)

- PE ratio is for equity holders only
- **EV/EBITDA covers debt structure** → better view of cash flow from operations
- EV/EBITDA = Enterprise Value ÷ EBITDA

### Calculating the Multiple

[Watch](https://youtu.be/GCzjetZZU54?t=757)

#### Enterprise Value (EV)

- **Formula**: Market Cap + Total Debt + Preferred Stock + Minority Interest - Cash
- **Market Cap**: Straightforward from Google/finance sites
- **Total Debt**: Long-term debt + Short-term debt (interest-bearing only)
  - Note: After IFRS16, also include "long-term operating lease liabilities"
  - Include convertible bonds, revolver facilities if separate line items
- **Preferred Stock**: Rare; if listed, add market cap; if unlisted, add book value
- **Minority Interest**: Value of non-owned subsidiary stake (for full company picture)
- **Cash**: "Cash and cash equivalents" from balance sheet (first line item)
- Example: $10B market cap + $3B debt - $1B cash = $12B EV

#### EBITDA

- **Formula**: Operating Income + Depreciation & Amortization (D&A)
- Operating Income: Middle of income statement
- D&A: From cash flow statement (non-cash expense that reduces asset value)
- Example: $1B operating income + $200M D&A = $1.2B EBITDA
- Available on Yahoo Finance or similar sites

#### Example Calculation

- EV = $12B, EBITDA = $1.2B → **EV/EBITDA = 10x**

### What EV/EBITDA Actually Means

[Watch](https://youtu.be/GCzjetZZU54?t=1077)

- Takes into account **debt AND equity** → values company regardless of capital structure
- **House analogy**:
  - House worth $1M with $500K mortgage
  - If bank rolls over mortgage → you pay $500K (equity value)
  - House price = $1M (equivalent to EV)
  - $50K gross rent = EBITDA (before interest/taxes)
  - $20K net rent = net income (after all deductions)
- **Depreciation & Amortization explained**: Asset value decreases over time (e.g., laptop bought for $2,000 worth less after 10 years)
- D&A added back because it's non-cash; shows true cash generating ability

### When to Focus on EV/EBITDA

[Watch](https://youtu.be/GCzjetZZU54?t=1281)

- Works for any company **except** banks and insurance companies
- **When PE is not useful**: Company with negative net income but strong operations
  - Example: Company B with $2B market cap, negative PE due to high interest expense
  - Look at capital structure: $2B debt used to build factory → efficient use
  - Revenue growing 30% → factory contributing to operations
  - EBITDA shows cash-generating ability despite net losses
  - Check if EBITDA covers interest expense
- **For low-growth companies** (<10% revenue): Use **historical EV/EBITDA** for peer comparison
- **For high-growth companies**: Use **forward EV/EBITDA** (post-QE era, companies use leverage for growth)

### EV/EBITDA Summary

[Watch](https://youtu.be/GCzjetZZU54?t=1321)

1. Even with net income losses, EV/EBITDA can spot good investments
2. Shows true value regardless of capital structure (Tesla had losses for a decade)
3. Forces attention to capital structure and fundamentals
4. Extremely helpful for manufacturing/heavy asset businesses

---

## 🏛️ 3. Federal Reserve & Market Liquidity

[Watch Section](https://youtu.be/GCzjetZZU54?t=1808)

- The Fed uses **two tools** to control market liquidity

### Fed Policy Rate

[Watch](https://youtu.be/GCzjetZZU54?t=1838)

- Interest rate set by the Fed/FOMC
- Impacts all borrowing rates (bonds, loans, mortgages)
- **Low rate** = cheap money → easier to borrow
- **High rate** = expensive money → harder to borrow
- Fed raises rates when: economy is good or inflation is high
- Fed lowers rates when: economy is doing bad
- Examples: Rates dropped in 2008 (Lehman) and 2020 (COVID); rose in 2004 and 2022

### Fed Balance Sheet

[Watch](https://youtu.be/GCzjetZZU54?t=1999)

- Represents Fed's assets (Treasury bonds, mortgage-backed securities)
- **Balance sheet increasing** = Fed buying bonds → more cash in market (QE)
- **Balance sheet decreasing** = Fed selling/maturing bonds → less cash in market (QT)
- Examples: Increased in 2008 & 2020 (crisis response); Decreased in 2018-19 & 2022+ (cooling economy)

### 📊 The Fed Liquidity Matrix (2x2)

[Watch](https://youtu.be/GCzjetZZU54?t=2128)

| | **Balance Sheet Increasing** | **Balance Sheet Decreasing** |
|---|---|---|
| **Rate Low** | Section A (Most Liquid) | Section C |
| **Rate High** | Section B | Section D (Least Liquid) |

#### Section A: Low Rate + Increasing Balance Sheet (Most Liquid)

[Watch](https://youtu.be/GCzjetZZU54?t=2198)

- Fed expects economy to slow → providing massive liquidity
- Liquidity hunts for **growth** (growth becomes scarce)
- Profitability doesn't matter → companies survive via debt/leverage
- **Strategy**: Invest in high-growth companies (e.g., NIO, Plug Power in 2020)

#### Section D: High Rate + Decreasing Balance Sheet (Least Liquid)

[Watch](https://youtu.be/GCzjetZZU54?t=2288)

- Growth is not as valued → liquidity is scarce
- **Strategy**: Focus on high profitability + margins
- Look at PE ratio → pick stocks with high margins, low valuation
- Traditional sectors: pharmaceuticals, food & beverage, manufacturing

#### Section C: Low Rate + Decreasing Balance Sheet (Moderate)

[Watch](https://youtu.be/GCzjetZZU54?t=2368)

- Some liquidity, but not enough for pure growth play
- Market looks for **both growth AND profitability**
- Tech stocks with both (like Nvidia) get attention
- Few stocks meet both criteria → concentrated investing

#### Section B: High Rate + Increasing Balance Sheet (Moderate)

[Watch](https://youtu.be/GCzjetZZU54?t=2438)

- Similar to Section C but interest rate is high
- Invest selectively

---

## 📊 4. Macro Indicators (10 Key Data Points)

[Watch Section](https://youtu.be/GCzjetZZU54?t=2210)

- Data grouped into 3 categories: **Job Market**, **Inflation**, **Economic Activities**
- These 3 topics are what the Fed monitors closely
- Monitoring these 10 data points covers **80-90% of the macro economy**
- Focus on **official data only** (Fed monitors official data)
- Find data on: Yahoo Finance, Investing.com (turn on alerts)

### 💼 Job Market Data

#### 1. Unemployment Rate

[Watch](https://youtu.be/GCzjetZZU54?t=2582)

- Percentage of unemployed workers actively seeking jobs vs total workforce
- **Fed's target**: ~4% (full employment)
- Interpretation:
  - **> 5.5%** = Weak economy
  - **4-5.5%** = Okay economy
  - **< 4%** = Strong economy
- Fed action: High unemployment → expansionary (cut rates/QE); Low unemployment → contractionary (raise rates/QT)

#### 2. Initial Jobless Claims

[Watch](https://youtu.be/GCzjetZZU54?t=2746)

- Number of people filing unemployment insurance for first time (weekly data)
- **Leading indicator** of unemployment rate
- Normal range: **250,000 - 350,000**
  - Above 350K = High (weak job market)
  - Below 250K = Low (strong job market)
- Same Fed action as unemployment rate

#### 3. Non-Farm Payrolls

[Watch](https://youtu.be/GCzjetZZU54?t=2861)

- Employment situation of bulk of US industry (excludes farming)
- Farming excluded because: highly cyclical + small share of employment
- Normal range: **50,000 - 250,000**
  - Above 250K = High (strong job market)
  - Below 50K = Low (weak job market)
- **Fed action is OPPOSITE**: High number → contractionary; Low number → expansionary

### 📈 Inflation Data

#### 4. CPI (Consumer Price Index) - Year-over-Year

[Watch](https://youtu.be/GCzjetZZU54?t=2918)

- Measures price increase of goods/services for consumers
- Look at **Year-over-Year** (removes volatility/seasonality, easier to communicate)
- **Fed's target**: 2%
  - Around 2% = Normal
  - Above 2% = High inflation
  - Below 2% = Low inflation
- Fed action: High CPI → contractionary; Low CPI → expansionary

#### 5. Core CPI - Year-over-Year

[Watch](https://youtu.be/GCzjetZZU54?t=3065)

- CPI **minus food and energy** (most volatile items)
- Removes external factors: geopolitical situations, natural disasters
- Gives Fed more balanced view of inflation
- Same mechanism as regular CPI

#### 6. PPI (Producer Price Index) - Month-over-Month

[Watch](https://youtu.be/GCzjetZZU54?t=3165)

- Measures price change of **manufacturing goods** (producer perspective)
- **Leading indicator** for CPI/Core CPI
- If production costs increase → companies pass to consumers → CPI rises
- Look at **Month-over-Month** (real-time tracking)
  - 0% to 0.2% = Okay inflation
  - Above 0.2% = High; Below 0% = Low
- Same Fed action as CPI

#### Additional: Core PCE Index (Not in Top 10 but Important)

[Watch](https://youtu.be/GCzjetZZU54?t=3223)

- Similar to Core CPI but broader scope
- Includes employer-paid healthcare
- Adjusted for changing consumer patterns
- **Fed's preferred** inflation measurement

### 📊 Economic Activities Data

#### 7. ISM Manufacturing PMI

[Watch](https://youtu.be/GCzjetZZU54?t=3234)

- Institute of Supply Management - Purchasing Managers Index
- Monthly survey of 300-400 manufacturing executives
- Covers: new orders, production, employment, inventories
- **Fed's favorite leading indicator** of real economy
- **Key number**: 50 = neutral (no change from previous month)
  - Above 55 = Strong expansion
  - Below 50 = Contraction
- Manufacturing = ~10-12% of US economy but leading indicator

#### 8. ISM Non-Manufacturing PMI

[Watch](https://youtu.be/GCzjetZZU54?t=3378)

- Covers **services sector** = ~70% of US economy
- More important indicator for overall growth/inflation
- Services: education, financial services, retail, hospitality
- Prices stickier (mostly human labor costs)
- **Fed monitors closely** for inflation defense
- Same measurement/action as manufacturing PMI

#### 9. Chicago PMI

[Watch](https://youtu.be/GCzjetZZU54?t=3399)

- Similar to ISM Manufacturing PMI but focused on **Midwest region**
- Why important:
  1. Chicago is a manufacturing hub (companies supply nationwide)
  2. Historically acts as **leading indicator** for nationwide ISM PMI
- Gives preview of ISM PMI 1-2 months ahead
- Same action as other PMI data

#### 10. Consumer Confidence Index

[Watch](https://youtu.be/GCzjetZZU54?t=3420)

- Measures consumer sentiment toward economic activity
- Monthly survey of 5,000 US households
- Questions about: income, employment status, business conditions
- **Key number**: 100 = neutral
  - 100-120 = Neutral
  - Above 120 = Strong sentiment
  - Below 100 = Weak sentiment
- Fed action: Strong sentiment → contractionary; Weak sentiment → expansionary

### Macro Indicators Summary

[Watch](https://youtu.be/GCzjetZZU54?t=3465)

1. Single data does NOT determine Fed's actions (holistic view needed)
2. Economic indicators need further analysis (e.g., COVID made all prior data useless)
3. Different data becomes important at different times (CPI became key in 2022)

---

## 🎯 5. Stock Investment Strategy

[Watch Section](https://youtu.be/GCzjetZZU54?t=3575)

> ⚠️ Caveats: This is the creator's personal strategy. Use as reference to build your own.

### Framework Recap: Fed Chessboard

[Watch](https://youtu.be/GCzjetZZU54?t=3625)

- **Interest Rate Impact**:
  - Low rate → WACC goes lower → company valuations go up
  - Low rate → bond yields drop → investors shift to stocks → higher demand
  - Low rate → companies benefit from reduced debt burden (especially growth companies)
- **Balance Sheet Impact**:
  - Increasing (QE) → easy to borrow, cheap money
  - Decreasing (QT) → harder to borrow, expensive money

### Four Stock Archetypes

[Watch](https://youtu.be/GCzjetZZU54?t=3818)

| Stock | Revenue Growth | Earnings Growth | PE Ratio | Debt/EBITDA | Profile |
|-------|---------------|-----------------|----------|-------------|---------|
| **A** | 5% | 5% | 10x | 1x | Stable, low growth, no debt |
| **B** | 10% | 10% | 20x | 3x | Moderate growth, some debt |
| **C** | 20% | 10% | 25x | 5x | High growth, high debt |
| **D** | 50%+ | Losses | N/A | N/A | Explosive growth, no earnings |

### Strategy by Fed Quadrant

#### Quadrant D (Least Liquid): High Rate + Decreasing BS

[Watch](https://youtu.be/GCzjetZZU54?t=3960)

- **Investment**: Max 20% of cash (or stay sideline)
- **Stock**: Company A
- Why: Low leverage keeps company solvent; low valuation less impacted by rising WACC
- High PE stocks trigger selloff mentality when rates rise

#### Quadrant C (Moderate): Low Rate + Decreasing BS

[Watch](https://youtu.be/GCzjetZZU54?t=4080)

- **Investment**: Max 50% of cash (selective)
- **Stock**: Company C (preferred) or B
- Why: High growth valued; high leverage benefits from rate decreases (refinance existing loans)
- Valuation justified by low WACC environment

#### Quadrant B (Moderate): High Rate + Increasing BS

[Watch](https://youtu.be/GCzjetZZU54?t=4140)

- **Investment**: Max 50% of cash (selective)
- **Stock**: Company B (preferred) or C
- Why: Moderate growth + moderate leverage; relatively okay under high rates

#### Quadrant A (Most Liquid): Low Rate + Increasing BS

[Watch](https://youtu.be/GCzjetZZU54?t=4200)

- **Investment**: 100%+ (aggressive, even take loans if possible)
- **Stock**: Company D
- Why: Companies rarely go bankrupt; cheap financing; liquidity hunts for growth
- ⚠️ **CAVEAT**: Must exit at right time
  - Sell on any signs of rates going back up or QE ending
  - Don't get swayed by "to the moon" narratives
  - Take profits at 20%, 50%, 100%, 200% gains

### Strategy Summary

[Watch](https://youtu.be/GCzjetZZU54?t=4296)

1. Ideal stock: Company D growth + Company A valuation/debt (rare)
2. Compare against **same sector peers** for relative valuation
3. Don't chase fast money → hold at least 6 months to 2 years
4. This is the creator's strategy → adapt for your own use

---

## 🧠 6. Investment Mindset

[Watch Section](https://youtu.be/GCzjetZZU54?t=4917)

> "Whatever skills and knowledge you have, if you don't have the right investment mindset, you'll most certainly fail."

### Problems with Existing Mindset Videos

[Watch](https://youtu.be/GCzjetZZU54?t=5017)

1. **Generalize** the "right" mindset → what works for one doesn't work for all
2. **Don't reflect reality** → Warren Buffett's 70-year mindset doesn't apply to most people
   - Asset prices rose much faster in past 10 years
   - High inflation forces people to pull investments for daily life

### 5 Key Mindset Principles

#### 1. Have Your Own Principle and Stick to It

[Watch](https://youtu.be/GCzjetZZU54?t=5230)

- Endless ways to invest: long-term, mid-term, short-term, value, narrative, options, etc.
- All strategies **can work** if done the right way
- Problem: A strategy that works for someone may not work for everyone
- Each strategy requires specific **soft skills and personality**
  - Long-term → patience & endurance
  - Value investing → instinct on numbers & industries
  - Scalping → gifted intuition on market movements
- **Know yourself**: assess your character objectively
  - Example: Creator has day job → can't trade all day; risk-averse → no speculation; strong with numbers → valuation focus

#### 2. Don't Get Swayed by Noise

[Watch](https://youtu.be/GCzjetZZU54?t=5430)

- Once you have your principle, **stick to it** and don't look elsewhere
- Creator didn't invest for ~10 years (2010s) while others got rich on stocks/crypto
- Still sees people getting rich daily (options, angel investments, crypto, trading) but **doesn't care**
- The moment you deviate → you become a **follower** instead of a **leader**
- See: "How I Lost $100K in One Day" video (when creator deviated from principles)

#### 3. Review Your Principle Regularly

[Watch](https://youtu.be/GCzjetZZU54?t=5660)

- People forget they could be wrong
- Market is a "shrewd animal" → strategy may not work as market evolves
- Test your principle regularly and thoroughly
- If not working → be nimble, but come up with **your own** logic (don't follow others)

#### 4. Remove Emotional Attachment from Money

[Watch](https://youtu.be/GCzjetZZU54?t=5700)

- Even professionals (hedge fund, PE) fail at personal investing due to emotions
- With other people's money: cold-hearted, logical, firm principles
- With own money: impatient, anxious, hot-tempered → completely different person
- After investing, consider it **someone else's money** (money given to company to improve)
- If you're mid-to-long-term investor checking account 3x/day → something is wrong

#### 5. Don't Talk to Others About Trades

[Watch](https://youtu.be/GCzjetZZU54?t=5850)

- When sharing trades → become agitated and anxious → hard to stick to principles
- Like recommending a restaurant → once you recommend it, you worry about friend's reaction
- Keeping investment thesis to yourself is generally more helpful
- At least that's how the creator feels (may not apply to everyone)

---

## 🎁 7. Simplified Way to Make Money (Bonus)

[Watch Section](https://youtu.be/GCzjetZZU54?t=5790)

> Simplified version of the investment strategy. Watch the 3 foundational videos first:
> 1. Stock Investing Strategy for Everyone
> 2. Macro Investing 101 for Beginners
> 3. You'll Certainly Fail Without the Right Mindset

### 📌 5 Critical Metrics to Monitor

[Watch](https://youtu.be/GCzjetZZU54?t=5980)

These 5 metrics were present in both April 2025 and March 2026 buying calls.

#### Metric 1: VIX > 30

[Watch](https://youtu.be/GCzjetZZU54?t=6120)

- CBOE Volatility Index → measures S&P 500 options volatility (30 days)
- Mathematically prices **fear** in the market
- Normal range: 15-20 (calm market); Can go as low as 10 (very optimistic)
- **Buy signal**: VIX > 30 (high fear = buying opportunity)

#### Metric 2: Fed Not Raising Rates

[Watch](https://youtu.be/GCzjetZZU54?t=6180)

- Most important metric for stock valuations
- Fed rate = basis for discount rate (WACC)
- Rate goes up → discount rate up → valuations down
- Rate goes down → discount rate down → valuations up
- **Buy signal**: Fed not indicating any rate increases

#### Metric 3: FINRA Margin Debt Decreasing

[Watch](https://youtu.be/GCzjetZZU54?t=6240)

- FINRA margin statistics = total debt in customer margin accounts (money borrowed to buy stocks)
- **Buy signal**: Margin debt on decreasing trend
  - Indicates market has been falling → deleveraging happening
  - More room for future leveraging
- Note: FINRA data released on **delayed basis** (~3-4 weeks after month end)

#### Metric 4: Clear Leading Sector

[Watch](https://youtu.be/GCzjetZZU54?t=6310)

- Market needs a **thematic engine** to attract institutional capital
- Examples: April 2025 → Max 7 stocks; March 2026 → Semiconductor stocks
- **Buy signal**: identifiable leading sector driving market

#### Metric 5: Leading Sector Earnings on Upward Trajectory

[Watch](https://youtu.be/GCzjetZZU54?t=6360)

- Leading companies must show dominance through **audited financials**
- Beat EPS and revenue estimates during macro panic
- Confirms business model is insulated from broader fear
- When fear goes away → high chance of upward trajectory

### Success Rate: 80-85%

[Watch](https://youtu.be/GCzjetZZU54?t=6420)

- Works 80-85% of the time (especially post-2008 QE era)
- Historical examples: 1997 Asia crisis, 2011 Euro crisis/US downgrade, 2018 Powell rate hike, 2020 COVID crash, April 2025, March 2026

### ⚠️ The 15-20% Bull Trap Scenarios

[Watch](https://youtu.be/GCzjetZZU54?t=6480)

When systemic imbalances cause the model to fail:

1. **Dotcom Bubble (2000-01)**: Leading sector fundamentals broke (Cisco, Yahoo revenue evaporated); rate cuts couldn't save 150x PE companies

2. **Accounting Scandals (2002)**: Enron, WorldCom, Tyco fabricated earnings → trust in SEC filings broke → market sank for 6 months

3. **Great Financial Crisis (2008)**: Commercial banking toxic MBS hadn't detonated; interbank lending froze → credit crunch → Fed injections couldn't stop panic

4. **2022 Fed Trap**: Fed called inflation "transitory" for a year → delayed reaction → long-lasting market fall

### Additional Risk Monitors

[Watch](https://youtu.be/GCzjetZZU54?t=6540)

1. **Credit Spread** (Bank of America US High Yield Index):
   - Premium junk corps pay over risk-free rate
   - Normal: 8-10%; Crisis: 15-20%+ (credit crunch → bankruptcies)

2. **Inflation**: High inflation → Fed can't act → model breaks (e.g., 1973 oil embargo)

3. **Accounting Fraud**: Distrust of financial reporting → catastrophic asset disposal (nobody can stop)

---

## 📝 Key Takeaways

1. **Valuation**: PE ratio and EV/EBITDA are fundamental → always use forward-looking metrics
2. **Macro matters**: Fed policies drive market liquidity → adapt strategy accordingly
3. **10 data points** cover 80-90% of macro economy
4. **Investment strategy** must match your personality and the Fed environment
5. **Mindset is crucial**: Have principles, stick to them, remove emotions
6. **5-metric checklist** for timing: VIX > 30, Fed not raising rates, margin deleveraging, leading sector, strong earnings
7. **No single rule** works for everyone → build your own strategy
