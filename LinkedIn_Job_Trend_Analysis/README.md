LinkedIn_Job_Trend_Analysis/README.md

 **Project Objective**:

Analyze LinkedIn job postings to identify the most in-demand skills , roles , and locations using data visualization and web-scraped job data.


 **Dataset Summary**:

Source: Web Scraped LinkedIn job postings (manually compiled)

Format: Excel (`.xlsx`)
**
Fields Included:

- Job Title

- City

- Posted Date

- Skills (comma-separated)

- Role

- Experience (Years)

- Company Name

- Presence (Binary Indicator)


**Tools & Technologies Used**

Power BI : For creating the dashboard and visuals

Python (BeautifulSoup, Pandas)**: For scraping and data cleaning (external to this report)

Excel : For manual preprocessing and formatting


**Analysis Performed**:

- Cleaned and transformed raw data (normalized multi-skill fields)

- Created dynamic dashboards using slicers (date, job title, city, company)

- Built visualizations to explore:

- Skill frequency

- Job demand by city and date

- Skill vs Role relationships

- Heatmaps of skill demand by location


 **Dashboard Highlights**:

Bar Chart: Job postings over time and city

Skill Frequency Chart: Top in-demand skills

Matrix Visuals:

Skills by Job Title

Skills by Role

Skills by City

Slicers : For Posted Date, Job Title, Company, and City


**How to Use:**

1. Open the `.pbix` file in Power BI Desktop

2. Use slicers to explore data (e.g., by city, date, job title)

3. Review visualizations to understand hiring trends and skills in demand


**Deliverables**:

- Cleaned Excel Dataset (`Cleaned_LinkedIn_Job_Trends.xlsx`)

- Power BI Dashboard (`.pbix`)

- Visual Summary (Skill/Role Matrix, Heatmaps)

- Project Report



**Conclusion:**

The LinkedIn Job Trend Analysis Dashboard offers powerful insights into job market trends using scraped job posting data. It highlights that:

Python, SQL, and Excel are consistently the most in-demand skills.

Roles such as Data Analyst and Business Analyst dominate job postings in tech cities like Delhi and Bangalore.

Companies like Accenture, Infosys, and IBM frequently appear in the hiring data.

The Skills vs Role Matrix helps identify role-specific skill expectations, aiding career planning for job seekers and hiring strategy for employers.

This project demonstrates how simple job data, when visualized correctly, can drive informed decisions for job market analysis, hiring, and personal skill development.
