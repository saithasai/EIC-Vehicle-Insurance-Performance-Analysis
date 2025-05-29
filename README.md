# EIC Vehicle Insurance Performance Analysis

## Problem Statement

**EIC**, once a leading motor insurance provider, faced consistent insurance losses between 2014 and 2018. Despite their vast customer base, the imbalance between **claims vs premiums** became unsustainable. This dashboard aims to explore their financial performance to identify key trends and patterns that led to their closure.  
[Dataset](https://data.mendeley.com/datasets/34nfrk36dt/1)  

The analysis includes an interactive dashboard showing:
- **Claims Trends**: Stacked area chart showing claim volumes by usage type over time
- **Premium vs Claims Scatter Plot**: Visual representation of the relationship between premiums and claims
- **Profitability Heatmap**: Color-coded performance metrics by vehicle usage segment
- **Policy Breakdown**: Detailed breakdown by vehicle type and year
- **Customer Demographics (Sex)** - Double doughnut charts showing claims and policies.

## Tools Used

* **Power BI**: For data modeling, DAX, and visualization
* **Excel**: For data extraction and cleaning

## Dashboard   
<img width="758" alt="Sale Overview" src="https://github.com/user-attachments/assets/e19f1805-406d-464c-95a8-88b7d1b1b1c0" />
<img width="758" alt="Sale Overview" src="https://github.com/user-attachments/assets/1786be5b-125b-4e19-a154-52584e763365" />

## Key Findings

### Financial Performance
- **Total Policies**: 508K policies issued
- **Total Premium**: $4 billion collected
- **Total Claims**: $9 billion paid out
- **Premium-Claim Ratio**: 44% (indicating severe losses)
- **Average Premium**: $8K per policy
- **Average Claim**: $18K per policy
- **Total Claims Count**: 38K claims

### Critical Business Insights

#### 1. Unsustainable Loss Ratio
The premium-claim ratio of only 44% indicates that EIC was paying out more than twice what they collected in premiums, making their business model fundamentally unsustainable.

#### 2. Premium-Claim Ratio Timeline
- **2014-2017**: Consistently negative ratios (red bars in chart)
- **Q2 2018**: Only profitable quarter (green bar showing ~220% ratio)
- This single profitable quarter was insufficient to offset years of losses

#### 3. Vehicle Type Analysis
**Policy Distribution by Vehicle Type:**
- Motor-cycle: 106.0K policies (highest volume)
- Truck: 94.1K policies
- Pick-up: 90.2K policies
- Automobile: 73.0K policies
- Bus: 65.6K policies

#### 4. Claims Pattern Analysis
- **Gender Distribution**: 
  - Male (Sex 1): 43% of claims
  - Female (Sex 0): 49% of claims
  - Other (Sex 2): 9% of claims
- Claims were fairly distributed across genders, indicating no significant gender-based risk pattern

#### 5. Profitability by Segment (2014-2018)
**Most Profitable Segments:**
- Agricultural Own Farm: Consistently high profitability (2309%-6115%)
- Special Construction: High profitability (968% in 2018)

**Least Profitable Segments:**
- Car Hires: Consistently low (37%-94% ratios)
- Fare Paying Passengers: Poor performance (32%-167%)
- General Cartage and Firefighting: Declining profitability

**Scatter Plot Chart: Premium vs Claims (Averages)**
- Most data points cluster in the lower-left quadrant (low premium, low claims)
- Some high-premium policies still resulted in disproportionately high claims
- Some points show high claims for relatively low premiums, indicating loss-making policies.
- A few dots toward the top-right suggest high-premium, high-claim policies—possibly large corporate or high-risk insurance cases.  
EIC may have underpriced many policies, making them financially unsustainable. Claims often far exceeded premiums, a key factor in the company’s 2019 shutdown.

**Ribbon Chart - Who claims most**
- General Cartage (yellow area) had the highest claims every year — this type of business caused the most losses.
- Own Goods (green) and Fare Paying Passengers (pink) also had a lot of claims.
- In 2018, claims suddenly dropped across all types — this likely means the company started to slow down or prepare to shut down.
- Some types like Taxi, Fire Fighting, and Special Construction had very few claims.
  The company (EIC) had too many claims in risky categories like General Cartage. These large claim amounts were a big reason why the company lost money and eventually shut down in 2019.

## Conclusions  

This project helps understand how misalignment in **premium pricing vs claim exposure** can collapse an insurance business. Power BI helped uncover:

* Which segments were driving losses.
* Which customer types were over-claiming.
* Historical claim trends across years and segments.
  
EIC's closure in 2019 was the inevitable result of:

1. **Structural Losses**:  Premiums being significantly lower than claims. Paying out $2.27 for every $1 collected in premiums
2. **Poor Risk Assessment**: A large number of high-risk segments being insured and inability to price policies appropriately for actual claim costs
3. **Segment Mismanagement**: Heavy exposure to unprofitable segments like car hires and passenger transport
4. **Insufficient Profitable Quarters**: Only one profitable quarter (Q2 2018) in the analyzed period, likely due to stricter underwriting or reduced claims.
5. Despite certain **profitable segments**, overall business model was unsustainable.

## Usage

This analysis serves as a case study for:
- Insurance risk management
- Business sustainability analysis
- Financial ratio interpretation
- Data-driven decision making in insurance

The insights demonstrate the critical importance of proper risk assessment and pricing in the insurance industry.   

👉[Live dashboard](https://app.powerbi.com/view?r=eyJrIjoiNGIxZmU0ZGMtZGI4YS00YTE5LWJlM2QtY2NhM2FmMTJjNmY1IiwidCI6IjNiN2YyODNhLWI1NzAtNGE5NS04ZTFmLTgwNzAwODAzODEwOSJ9) 
