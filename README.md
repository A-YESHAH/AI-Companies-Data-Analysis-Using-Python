# AI Companies Data Analysis Using Python
This project analyzes AI companies’ financial performance using Python. The focus is on exploring relationships between R&D Spending, AI Revenue, Revenue Growth, and Stock Impact. The dataset contains yearly financial figures, enabling trend analysis, correlation studies, and visual comparisons.

# Dataset
File: ai_financial_market_daily_realistic_synthetic.csv
## Key Columns:
- Date → Reporting date of the record
- Company → AI company name
- R&D_Spending_USD_Mn → Research and Development spending in million USD
- AI_Revenue_USD_Mn → AI-related revenue in million USD
- AI_Revenue_Growth_% → Percentage growth in AI revenue compared to the previous year
- Event → Key events like product launches, mergers, or announcements
- Stock_Impact_% → Stock price percentage change due to events

# Analysis Steps
- Data Import & Cleaning
- Loaded CSV using Pandas
- Grouped yearly data for OpenAI’s R&D spending and revenue
- Trend Analysis
- Plotted AI Revenue (blue) vs R&D Spending (red) over time for OpenAI
- Correlation Analysis
- Checked relationships between:
- R&D Spending and AI Revenue
- AI Revenue Growth and Stock Impact

# Tech Stack
- Python → Data manipulation and analysis
- Pandas → Data cleaning, grouping, and correlation calculation
- Matplotlib → Trend visualization

