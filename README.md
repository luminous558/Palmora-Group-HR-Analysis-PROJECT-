# Palmora-Group-HR-Analysis-PROJECT-
This is my Second Case Study (Project) to work on as a Data Analyst during Incubator Hub Program


# $${\color{Aqua}INTRODUCTION}$$



In light of recent public scrutiny surrounding gender inequality at The Palmoria Group, a prominent manufacturing company based in Nigeria, the organization has found itself at a critical crossroads. A damning media headline, “Palmoria, the Manufacturing Patriarchy,” has not only cast a shadow over the company’s internal culture but also threatens its broader business ambitions, particularly its expansion into new regions and international markets.

The CEO, Mr. Ayodeji Chukwuma, has expressed deep concern about the implications of this negative press and the potential uncovering of systemic issues such as gender pay disparities and unequal growth opportunities. Determined to take swift and meaningful action, he has tasked the Chief Human Resources Officer, Mr. Yunus Shofoluwe, with spearheading a comprehensive review of the company’s HR practices through a gender equity lens.

In response, Mr. Shofoluwe has engaged the expertise of an HR Analytics professional to lead a strategic project aimed at uncovering and addressing gender-based disparities within the workforce. This initiative will involve an in-depth analysis of HR data across Palmoria’s three regional operations, with the goal of identifying areas of concern, highlighting patterns of inequality, and providing actionable, data-driven recommendations to foster a more inclusive and equitable workplace.

This project represents a pivotal step in restoring public trust, safeguarding the company’s reputation, and building a future where gender equality is not just a goal but a foundational principle of Palmoria’s organizational culture.


# $${\color{Aqua}OBJECTIVE \space \space STATEMENT}$$

The primary objective of this project is to identify, analyze, and address gender-related disparities within The Palmoria Group’s workforce across its three regional operations. By leveraging HR analytics, the project aims to support the company’s leadership in making informed, data-driven decisions that promote gender equality and foster a more inclusive organizational culture. Specifically, the objectives are to:

- **Diagnose existing gender imbalances** in recruitment, compensation, promotions, training, leadership representation, and employee turnover across all regions.

- **Assess the gender pay gap** by analyzing salary data across roles, departments, and seniority levels.

- **Evaluate policy and process gaps** that may contribute to systemic gender inequality, including hiring practices, performance evaluations, and career development opportunities.

- **Benchmark Palmoria’s performance** against industry standards and best practices in gender equity.

- **Generate actionable insights and recommendations** for leadership to implement sustainable strategies that promote gender equality.

- **Support reputational recovery** and reinforce the company’s commitment to diversity, equity, and inclusion, particularly as Palmoria positions itself for expansion into new markets.


# $${\color{Aqua}PROJECT \space EDA, \space Gender \space Equality \space and \space Pay \space Analysis}$$

After the Palmoria employee Data was Imported into Power BI.

proper cleaning was done i.e)
1. employees without salaries and departments indicated as "NULL" was removed 
2. A generic gender status was assigned to employees who refused to disclose their gender.
   
![Project Screenshot ](https://github.com/user-attachments/assets/b656db6b-2ad6-4b6e-80cc-cd7615da11f0)


## 1. Gender Distribution Analysis

This shows the representation of genders across the company.

$${\color{orangered}Below \space are \space the \space Steps \space for \space carrying \space out \space the \space Analysis;}$$

- Determine overall gender distribution (% Male, % Female, % Non disclosed).

Break down by:

- Regions ( Abuja, Lagos, Kaduna)

- Departments ( Accounting, Legal, Sales, etc.)


## 2. **Performance Rating Analysis by Gender**

This Explore if gender biases exist in employee performance evaluations.

$${\color{orangered}Below \space are \space the \space Steps \space for \space carrying \space out \space the \space Analysis;}$$

- Employees by gender was grouped and average performance ratings was calculated

- Distribution of ratings (i.e., how many males vs. females got top ratings).

Ratings was done by; 

   - Region

   - Department

![dept_rating](https://github.com/user-attachments/assets/d88772c5-c71a-4801-8b29-d16a779ed7d4)



![merging ](https://github.com/user-attachments/assets/1d283f11-e8b5-4eb8-b521-ff4dd2059b3d)

## 3. **Salary Structure & Gender Pay Gap Analysis**

pay inequality was Identified and regions/departments where it is most severe.

$${\color{orangered}Below \space are \space the \space Steps \space for \space carrying \space out \space the \space Analysis;}$$

Average salary was calculated by:

   - Gender (overall)

   - Gender & department

   - Gender & region



## 4. **Minimum Salary Compliance Check**

Compliance with the $90,000 minimum salary regulation was ensured

$${\color{orangered}Below \space are \space the \space Steps \space for \space carrying \space out \space the \space Analysis;}$$

Employees earning was filtered as < $90,000 and count them.

Salary data was segmented into $10,000 bands:

$10k–$20k, $20k–$30k, ..., $90k+

And it was breakdown by region.


![salary band](https://github.com/user-attachments/assets/6edd1802-80fc-4498-8d87-4712ed4bcc68)



![replace](https://github.com/user-attachments/assets/14718fdc-41aa-4b3c-b4b9-8fffb9f04992)


## 5. **Bonus Allocation & Total Compensation Analysis**

Bonus rules to compute additional compensation and regional totals was applied 

$${\color{orangered}Below \space are \space the \space Steps \space for \space carrying \space out \space the \space Analysis;}$$

Performance rating dataset with bonus rules was merged 

below Calculations was applied 

- Bonus amount per employee

- New total compensation (salary + bonus)

  - Group by region to get:

- Total bonus payout

- Total compensation payout

<img width="1365" height="728" alt="visualization 3 " src="https://github.com/user-attachments/assets/a3bd305c-c599-4762-8cde-bf7f4c114a9f" />


# ✅ $${\color{Aqua}KEY \space \space INSIGHT}$$


### 🔹 1. **Gender Distribution**


Overall imbalance: Males constitute a significantly higher percentage of the workforce (49.2%), with females underrepresented, especially in Legal and Accounting roles.

Regional differences: Kaduna has the lowest female representation (<46%), while Abuja and Lagos has the highest.

Departmental variation: Departments such as Accounting and Legal are heavily male-dominated, while Marketing and Training Deartment have more gender balance.


### 🔹 2. **Performance Ratings by Gender**


Bias patterns: On average, male employees receive higher performance ratings, particularly in Kaduna.

Rating disparity: A higher proportion of males fall into the top performance band (4–5), which directly affects bonus allocation and promotion eligibility.




### 🔹 3. **Salary Structure & Gender Pay Gap**


Pay gap exists: Across all departments, male employees earn on average 10–15% more than their female counterparts.

Most affected areas:

Kaduna and Lagos show the widest pay gaps.

Accounting, Legal, and Production Management have the most pronounced disparities.


### 🔹 4. **Minimum Salary Compliance**


Non-compliance risk: A significant portion of the workforce (e.g., 18%) earns below $90,000 particularly in Production and Legal Service.

Salary bands: Most employees fall into the Above $90,000 range, with higher bands.


### 🔹 5. **Bonus Allocation & Total Compensation**


Performance-driven inequality: Bonus payouts favor high-rated (mostly male) employees, compounding existing pay gaps.

Total payout analysis:

Kaduna receives the highest total payout due to more balanced ratings.

Lagos lags in bonus distribution and overall compensation equity.


# 🛠 $${\color{Aqua}RECOMMENDATIONS}$$


### 📌 1. **Promote Gender Equity Initiatives**


After Gender targets for recruitment was Implemented, especially in underrepresented departments (e.g., Accounting, Legal).

I recommended that the Company should Launch mentoring programs to support women in career progression and leadership development.

And Introduce unconscious bias training for hiring managers and performance reviewers.


### 📌 2. **Address Pay Inequities**


Organization should Conduct an annual pay audits, and adjust compensation where unjustified gaps exist.

Organization should Standardize pay bands by role, not by gender or region.

And Prioritize corrections in high-gap departments like Accounting and Legal.


### 📌 3. **Ensure Regulatory Compliance**


Company should Review salaries below $90,000 and bring them up to meet legal requirements.

And Budget for phased adjustments in departments with many sub-threshold earners.

and Company should Communicate changes transparently to foster trust and accountability.


### 📌 4. **Improve Performance Evaluation Fairness**


Campany needs to Review and recalibrate rating systems to reduce subjectivity.

And Introduce 360-degree feedback mechanisms to ensure diverse input in evaluations.

Company should Track rating trends by gender to detect and correct systemic bias.


### 📌 5. **Redesign Bonus Structure (Optional Enhancement)**


Tying bonuses partly to team or department goals to reduce individual performance bias should well monitored by the Organization 

And Introduce diversity-based incentives for departments that show measurable equity improvements.




# $${\color{Aqua}PROJECT \space VISUALIZATION \space DASHBOARD}$$

Below is the Visualisation of PALAMORA Organization that shows Analysis of Gender Pay Gap, Gender Rating by Region and Deartment, Bonus Rate, Salary Band and so...
The Visualization Include Slicer to Navigate through the Visualizations Dashboard, and below Images shows Answers to Case scenario that was asked by the Company Managements.


![20250718_221514](https://github.com/user-attachments/assets/9cf84cae-2ccf-420d-88e2-05d690ababfa)



Using Gender Slicer to navigate Visualizations Dashboard.

1.
<img width="619" height="418" alt="SLICER 1" src="https://github.com/user-attachments/assets/f801bcb3-71ef-4a64-b90c-e6b6ae61fb78" />


2.
<img width="622" height="417" alt="SLICER 2" src="https://github.com/user-attachments/assets/95e8a918-832f-4889-bcb6-971cbc45e7dd" />






# 🧩 $${\color{Aqua}PROJECT \space \space CONCLUSION}$$



The gender inequality concerns raised at The Palmoria Group are not only valid but also supported by clear data patterns across regions and departments. The analysis has revealed systemic issues — including gender imbalance in workforce distribution, disparities in performance ratings, and a persistent gender pay gap — particularly concentrated in key operational areas like Accounting and Legal.

Furthermore, compliance risks have been identified, as a significant number of employees currently earn below the newly mandated minimum salary threshold of $90,000. These gaps in pay, performance evaluation, and compensation allocation pose not just internal culture challenges, but also reputational and legal risks, especially as Palmoria positions itself for international expansion.

However, this also presents a unique opportunity for the organization to lead by example. With a data-driven roadmap now in place, Palmoria can take decisive steps toward fostering an inclusive, equitable, and future-ready workplace. By implementing the recommended strategies — from targeted hiring and pay adjustments to performance review reforms and compliance checks — leadership can rebuild trust, improve employee morale, and reposition Palmoria as a forward-thinking employer of choice.

The path to gender equity at Palmoria begins with action — and the data has made the next steps clear.


# The PDF file of the DASHBOARD  👇👇

[PALMORA VIZ.pdf](https://github.com/user-attachments/files/21333587/PALMORA.VIZ.pdf)
