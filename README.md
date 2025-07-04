# Palmora-Group-HR-Analysis-PROJECT-
This is my Second Case Study (Project) to work on as a Data Analyst during Incubator Hub Program


# $${\color{blue}INTRODUCTION}$$



In light of recent public scrutiny surrounding gender inequality at The Palmoria Group, a prominent manufacturing company based in Nigeria, the organization has found itself at a critical crossroads. A damning media headline, “Palmoria, the Manufacturing Patriarchy,” has not only cast a shadow over the company’s internal culture but also threatens its broader business ambitions, particularly its expansion into new regions and international markets.

The CEO, Mr. Ayodeji Chukwuma, has expressed deep concern about the implications of this negative press and the potential uncovering of systemic issues such as gender pay disparities and unequal growth opportunities. Determined to take swift and meaningful action, he has tasked the Chief Human Resources Officer, Mr. Yunus Shofoluwe, with spearheading a comprehensive review of the company’s HR practices through a gender equity lens.

In response, Mr. Shofoluwe has engaged the expertise of an HR Analytics professional to lead a strategic project aimed at uncovering and addressing gender-based disparities within the workforce. This initiative will involve an in-depth analysis of HR data across Palmoria’s three regional operations, with the goal of identifying areas of concern, highlighting patterns of inequality, and providing actionable, data-driven recommendations to foster a more inclusive and equitable workplace.

This project represents a pivotal step in restoring public trust, safeguarding the company’s reputation, and building a future where gender equality is not just a goal but a foundational principle of Palmoria’s organizational culture.


# $${\color{blue}OBJECTIVE \space \space STATEMENT}$$

The primary objective of this project is to identify, analyze, and address gender-related disparities within The Palmoria Group’s workforce across its three regional operations. By leveraging HR analytics, the project aims to support the company’s leadership in making informed, data-driven decisions that promote gender equality and foster a more inclusive organizational culture. Specifically, the objectives are to:

- **Diagnose existing gender imbalances** in recruitment, compensation, promotions, training, leadership representation, and employee turnover across all regions.

- **Assess the gender pay gap** by analyzing salary data across roles, departments, and seniority levels.

- **Evaluate policy and process gaps** that may contribute to systemic gender inequality, including hiring practices, performance evaluations, and career development opportunities.

- **Benchmark Palmoria’s performance** against industry standards and best practices in gender equity.

- **Generate actionable insights and recommendations** for leadership to implement sustainable strategies that promote gender equality.

- **Support reputational recovery** and reinforce the company’s commitment to diversity, equity, and inclusion, particularly as Palmoria positions itself for expansion into new markets.


# $${\color{blue}PROJECT \space EDA, \space Gender \space Equality \space and \space Pay \space Analysis}$$

After the Palmoria employee Data was Imported into Power BI.

proper cleaning was done i.e)
1. employees without salaries and departments indicated as "NULL" was removed 
2. A generic gender status was assigned to employees who refused to disclose their gender.


## 1. Gender Distribution Analysis

This shows the representation of genders across the company.

Below are the Steps for carrying out the Analysis;

- Determine overall gender distribution (% Male, % Female, % Non disclosed).

Break down by:

- Regions ( Region Abuja, Lagos, Kaduna)

- Departments ( Engineering, Legal, Sales, etc.)


 2. **Performance Rating Analysis by Gender**

This Explore if gender biases exist in employee performance evaluations.

Below are the Steps for carrying out the Analysis;

- Employees by gender was grouped and average performance ratings was calculated

- Distribution of ratings (i.e., how many males vs. females got top ratings).

Ratings was done by; 

   - Region

   - Department


 3. **Salary Structure & Gender Pay Gap Analysis**

pay inequality was Identified and regions/departments where it is most severe.

Below are the Steps for carrying out the Analysis;

Average salary was calculated by:

   - Gender (overall)

   - Gender & department

   - Gender & region

 4. **Minimum Salary Compliance Check**

Compliance with the $90,000 minimum salary regulation was ensured

Below are the Steps for carrying out the Analysis;

Employees earning was filtered as < $90,000 and count them.

Salary data was segmented into $10,000 bands:

$10k–$20k, $20k–$30k, ..., $90k+

And it was breakdown by region.

 5. **Bonus Allocation & Total Compensation Analysis**

Bonus rules to compute additional compensation and regional totals was applied 

Below are the Steps for carrying out the Analysis;

Performance rating dataset with bonus rules was merged 

below Calculations was applied 

- Bonus amount per employee

- New total compensation (salary + bonus)

  - Group by region to get:

- Total bonus payout

- Total compensation payout
