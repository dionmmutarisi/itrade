# itrade Stock Recommendation Algorithm

This project provides an algorithm to recommend the best stocks for investment based on user-defined preferences, such as industry, establishment year, and ESG criteria.

---

## Features
1. **Industry Preference**:
   - Filter stocks by industry, such as Mining, Entertainment, Electronics, etc.
2. **Establishment Year**:
   - Choose stocks from companies established before a specific year.
3. **ESG (Environment, Social, Governance) Criteria**:
   - Prioritize socially responsible investments with High, Medium, or Low ESG scores.
4. **Performance-Based Sorting**:
   - Stocks are sorted by performance to ensure optimal recommendations.
5. **Customizable Recommendations**:
   - Select the number of stocks to be recommended (1-100).

---

## How It Works
1. The algorithm reads a CSV file (`stocks.csv`) containing stock information, including:
   - **Performance**: Numerical score indicating stock performance.
   - **Industry**: Industry sector of the company.
   - **FoundationYear**: Year the company was established.
   - **Environment**, **Social**, **Governance**: ESG criteria values.
2. Users are prompted to define their preferences for:
   - Industry
   - Establishment Year
   - ESG Criteria
3. Based on these inputs, the algorithm filters and ranks stocks to meet the user's criteria.

