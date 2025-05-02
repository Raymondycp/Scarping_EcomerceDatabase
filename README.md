# Scraping Ecommerce Database

#### Project Goals

- Build an e-commerce snack market analysis database for major Hong Kong retail websites (Lung Fung, ParknShop, Wellcome, HKTV mall).  
- Collect product data via scraping, clean and categorize it, store in PostgreSQL, and analyze/visualize using PowerBI.  
- Provide data-driven insights to predict market trends and inform strategies.

#### Technical Implementation

- **Scraping Process** (Lung Fung example):  
  1. Collect URLs for all snack product pages (7 pages).  
  2. Extract details from each product page (brand, price, stock, etc.).  
  3. Clean and categorize data using Pandas.  
  4. Save as CSV and plan PostgreSQL insertion.  
- **Database Design**:  
  - Clear structure with product and scraping details tables.  
  - Foreign key constraints ensure data integrity.  
- **Visualization**:  
  - Attempted Seaborn for category count plots (failed due to module error).  
  - Planned PowerBI for advanced visualization.

#### Challenges and Solutions

- **Data Inconsistency**: Different websites have varying category labels and structures, addressed via keyword mapping and regex.  
- **Missing Values**: High missing rates in Lung Fung’s BrandZH, Origin, etc., requiring further imputation or inference.  
- **Team Collaboration**: Agile methods and multi-platform communication (Slack, GitHub) ensured progress; in-person meetings resolved network issues.

#### Team Collaboration

- **Documentation**: Structure Google Docs and GitHub with clear folders (e.g., scraping scripts, cleaning scripts, database scripts).  
- **Progress Tracking**: Set milestones in ClickUp (e.g., complete scraping, database design, visualization).  
- **Knowledge Sharing**: Hold regular tech-sharing sessions on scraping, cleaning, or PowerBI best practices.

---

