# Travel-Analytics-Project
This project analyzes a tourism company's customer dataset to uncover behavioral patterns, demographic segments, and conversion drivers. Nine strategic business questions are explored through interactive Tableau dashboards and supporting Excel pivot tables, culminating in data-driven recommendations for sales optimization.

**Key Findings**
**Age Distribution**

- The 30–39 age bracket is the largest segment (~43% of customers, 1,776 records)
- Customers under 20 have the highest conversion rate at 66.7%, despite being a small group
- The 20–29 group offers the best balance of volume and conversion (28.9%)
- Customers aged 60+ show 0% conversion — pitches to this group are ineffective

**Income vs Trips Correlation**

- Income alone is a poor predictor of travel frequency
- Most customers make 1–4 trips/year regardless of income bracket
- A few extreme outliers (19–22 trips) likely represent data anomalies or business travelers

**Occupation & Pitch Satisfaction**

- Large Business professionals rate pitches highest (avg: 3.24 / 5)
- Salaried employees follow at 3.09, Small Business owners at 2.99
- Score 3 ("Neutral") is the modal response across all occupations — pitches are adequate but not compelling
- Satisfaction aligns with conversion: Large Business also has the highest purchase rate (29.1%)

**Customer Segmentation**

- Three natural segments emerge from property star preference:
- SegmentSizeStar PrefProfileBudget/Mid-Range~62% (2,541)3-starMarried, 30–39, average incomeComfort Traveler~21% (863)4-starMixed marital status, moderate incomePremium Seeker~17% (724)5-starHigher income, single/married, passport holders

**Highest-Converting Segments**

- SegmentConversion RateUnder-20 age group66.7%Passport holders35.8%Single marital status36.4%Large Business occupation29.1%Executive designation30.0%
- Top customer profile: Young (under 30) + Single + Passport Holder + Executive/Salaried

**Income & Product Choice**

- Income clearly tracks product tier pitched:
- ProductAvg Income (Salaried)Conversion RateBasic~19,91930.0%Standard~26,48216.1%Deluxe~23,04511.6%Super Deluxe~31,1317.6%King~34,3628.7%
- Despite correct income-to-tier matching, premium product conversion rates are disproportionately low — a potential pricing or value-communication issue.

**Contact Type Conversion**

- Contact TypeCustomersConversion RateCompany Invited1,21022.7%Self Enquiry2,91817.9%
- Proactively contacted customers convert ~27% better than self-inquirers, suggesting effective prospect targeting by the company's outreach program.

**City Tier Sales Performance**

- City TierCustomersConversion RateTier 1 (Major Metro)2,678 (64.9%)16.5%Tier 2 (Mid-size)162 (3.9%)26.5%Tier 3 (Smaller Cities)1,288 (31.2%)24.1%
- Tier 2 is severely under-penetrated — highest efficiency market with only 162 customers reached.

**High-Star Customers: Product & Follow-ups**

- Product vs Conversion (4+ star preference customers):
- Product PitchedConversion RateBasic37.5%Standard17.8%Deluxe13.4%King15.6%Super Deluxe8.7%
- Follow-ups vs Conversion (4+ star preference customers):
- Follow-upsConversion Rate214.3%319.5%423.5%530.9%648.6%
- Sales persistence is strongly rewarded — each additional follow-up meaningfully increases conversion probability.

**Additional Insights**

- Pitch duration matters: Converted customers experienced longer pitches on average (17.0 min vs 15.2 min). A minimum pitch duration standard could be a quick win.
- Optimal group size: Customers traveling solo (1 person) or in very large groups (5+) show 0% conversion. The sweet spot is 2–4 travelers.
- Designation paradox: Junior Executives convert at 30%; senior VPs/AVPs convert at under 9% despite higher incomes — possibly because senior staff already have corporate travel benefits.
- Single vs Unmarried: These two categories have meaningfully different conversion rates (36.4% vs 24.3%) — a distinction worth leveraging in messaging.
- Car ownership (unexplored): Non-car-owners may be disproportionately receptive to all-inclusive packaged travel. This variable was not analyzed in the 9 questions.

**Strategic Recommendations**

- Launch targeted outreach to passport-holding + single + Executive customers in Tier 2 and Tier 3 cities
- Implement a minimum 4 follow-up standard for all leads; 5–6 follow-ups for high-star preference customers
- Enforce income-to-product-tier matching in all pitches — no 30k+ earner should receive only a Basic offer
- Scale the Company Invited outreach program using a lead-scoring model built on the conversion signals identified
- Build youth travel packages targeting the high-converting under-20 and 20–29 segments
- Run a Tier 2 city expansion pilot across 3–5 new cities to test conversion rate scalability
- Develop a family travel product line for married customers with children (the largest segment)
- Investigate and redesign premium product pricing/value — King and Super Deluxe packages underperform significantly
- Build a CRM-based lead scoring system to automate segmentation and pitch assignment

**Tools Used**
- Microsoft Excel — Data cleaning, pivot tables, calculated fields, conversion rate tables
- Tableau Desktop — Interactive dashboard creation, visual analytics, cross-filtering
