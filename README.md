# DA_Store_Expansion_Strategy_Analysis


## Project Background

The telecommunications company is currently facing a critical decision regarding strategies to accelerate prepaid gross subscriber additions. The President of Mobility has mandated an evaluation of two pivotal options:

#### Option 1: Partnering with a Leading Retail Chain

This option involves collaborating with a prominent retail chain to enhance subscriber additions.

#### Option 2: Building Direct Stores

This option focuses on establishing direct stores to increase subscriber numbers.

## Evaluation Criteria

The assessment will be based on the following key factors:

- **Revenue:** Estimating potential earnings from both options, factoring in subscriber growth projections and average revenue per user (ARPU).

- **Costs:** Including initial setup costs, operational expenses, marketing investments, and any other pertinent financial outlays for each option.

- **Margins:** Calculating both gross and net margins to understand the profitability of each strategy.

- **Net Present Value (NVP):** Utilizing NVP calculations to gauge the financial viability of each option, considering the time value of money.

Utilizing Microsoft Excel to generate comprehensive reports and charts for conducting comparisons.

## KPIs and formulas
 - Gross income/profit = revenue – cost
 - Monthly Revenue  = (#store*(#unit + #adjust))  *  $ prepaid
 - Total Revenue = SUM(monthly revenue)
 - Cost = churn (rate * revenue) + commission(#unit * $commission) + Share_Split(revenue* split_rate) +  rent_fixture(#location* fee)



## Results

### Average Case

- **Duration:** 3-19 months
- **Comparison:** Leading Retail Chain over Direct Store
- **Lowest Margin:** 
  - **Direct Store:** 5 months later: - $2,907,000
- **Visual Representation:**
  ![Average Case](https://github.com/yrenn/DA_Store_Expansion_Strategy_Analysis/assets/118937529/a52b2f2b-12e6-4767-916e-b916a700f1cd)

### Best Case

- **Duration:** 4-17 months
- **Comparison:** Leading Retail Chain over Direct Store
- **Lowest Margin:**
  - **Direct Store:** 4 months later: - $2,400,000
- **Visual Representation:**
  ![Best Case](https://github.com/yrenn/DA_Store_Expansion_Strategy_Analysis/assets/118937529/89e1cf91-9697-4f4f-b476-e5a8f7eeba2e)

### Worst Case

- **Duration:** 3-20 months
- **Comparison:** Leading Retail Chain over Direct Store
- **Lowest Margin:**
  - **Direct Store:** 6 months later: - $3,682,000
- **Visual Representation:**
  ![Worst Case](https://github.com/yrenn/DA_Store_Expansion_Strategy_Analysis/assets/118937529/89e1cf91-9697-4f4f-b476-e5a8f7eeba2e)


#### Partnering with an Established Retail Chain

- **Pros:**
  - **Leveraging Established Customer Base:** Access to an existing pool of customers through the retail chain's reputation.
  - **Lower Initial Investment:** Likely reduced setup costs compared to building direct stores.

- **Cons:**
  - **Profit Sharing:** Shared profits with the retail chain.
  - **Limited Control:** Limited control over customer experience and branding.

#### Building Direct Stores

- **Pros:**
  - **Full Control:** Complete control over branding, customer experience, and profits.
  - **Long-term Potential:** Potential for higher profit margins in the long run.

- **Cons:**
  - **Higher Initial Investment:** Higher setup costs and operational expenses.
  - **Operational Challenges:** Time-intensive setup and operational challenges.

## Difficulty and lesson learned

### Prepaid Market Prediction

- **Range:** Best Case to Worst Case Scenario

### Revenue Calculation

- **Method:** Sum of Monthly Revenue for the Predicted Period

### Finance Model and Prediction

#### Long-Term Margin Comparison

- **Comparison:** Leading Retail Chain vs. Direct Store
- **Analysis Period:** Long-term (Beyond 20 months)
- **Prediction Focus:** Margin Trends and Predictions

#### Short-Term Margin Comparison

- **Comparison:** Leading Retail Chain vs. Direct Store
- **Analysis Period:** Short-term (Within 20 months)
- **Prediction Focus:** Margin Trends and Predictions


## Potential Impact and Further Improvements

#### Adjustment Parameters

To refine the evaluation and make a well-informed decision, consider adjusting the following parameters:

- **Prepaid Price (KPI):** Modifying the prepaid_price can impact overall revenue. Test different price points to assess their effect on the financial model.

- **Share Split (KPI):** Adjusting the share_split parameter can alter profit distribution. Test various share split ratios to find the most favorable balance.

## Best Portfolio: Retail Chain Store and Direct Stores

#### Optimal Combination

Based on the adjusted parameters and thorough analysis, the best portfolio could involve a hybrid approach, combining both strategies for maximum impact:

- **Leading Retail Chain Stores:** Leverage the retail chain's customer base for immediate market penetration and brand recognition.
- **Direct Stores:** Establish direct stores in strategic locations to ensure complete control over branding and customer experience.

#### Further Adjustments

Continuously monitor the market and adjust the KPIs (e.g., prepaid_price, share_split) as needed. Regularly revisit the strategy based on changing market dynamics and consumer behavior to maintain a competitive edge and maximize profitability.





