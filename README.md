# Insurance Analysis Report

# 💠 Project Overview

The Insurance Analysis Report dashboard, built with Power BI, provides a comprehensive overview of key performance indicators (KPIs) across new policies, cross-selling initiatives, and renewals within an insurance business. It tracks achievement rates against targets for new policies, analyzes cross-sell opportunities, and monitors renewal performance. The dashboard also offers insights into opportunity distribution by revenue, product, and responsible executive, enabling stakeholders to identify top performers, pinpoint areas for improvement in sales and renewal processes, and optimize resource allocation for enhanced business growth and customer retention.

# 💠 Problem Statement:

* How effectively are we acquiring new customers and achieving our new policy targets?

* What is our success rate in cross-selling to existing customers, and how can we improve it?

* How are we performing in terms of policy renewals, and what factors contribute to high or low renewal rates?

* Which executives are driving the most opportunities and revenue in new, cross-sell, and renewal segments?

* What are the most popular product types, and how do they contribute to overall opportunities?

* Are there specific areas of the business (e.g., particular executives, product types) that require more attention or training to improve performance?

* How can we leverage these insights to optimize sales strategies, improve customer retention, and increase overall revenue?

# 💠 Data Source

The dashboard utilizes data from internal insurance sales and policy management systems. It encompasses information related to new policy acquisitions, cross-sell activities, and policy renewals, including targets, actual achievements, revenue figures, opportunity counts, and executive performance data.

### The source tables used for this dashboard are:

- brokerage

- fees

- budget

- invoice

- meeting

- opportunity

# 📂 Download
(Not applicable as this is an image, not a live dashboard with a download link.)

# 💠 Data Preparation

The data preparation phase for this dashboard likely involved:

- Data extraction from csv Files 

- Cleaning and standardizing data formats (e.g., date formats, numerical values).

- Handling missing values or inconsistencies.

- Creating calculated columns and measures (e.g., achievement percentages) from the raw data.

- Establishing relationships between different tables (brokerage, fees, budget, invoice, meeting, opportunity) for data modeling and analysis.

# 💠 Project Dashboard:

## 🎯 KPIs

### New Business:

* New Policy Achievement %: 17.95% - Indicates significant underperformance against the target for new policy acquisitions.

* New Invoice Achievement %: 4.21% - Suggests an even lower achievement rate for generating invoices from new policies, highlighting a potential bottleneck in the sales-to-invoicing process.

### Cross-sell:

* Cross Sell Policy Achvmnt %: 64.94% - Shows a moderately successful rate in cross-selling policies, indicating room for improvement to meet or exceed targets.

* Cross sell Invoice Achvmnt %: 15.14% - Similar to new policies, the invoice achievement for cross-sells is low, suggesting challenges in converting cross-sell policies into billed revenue.

### Renewal:

* Renewal Policy Achvmnt %: 150.23% - An exceptionally high achievement, indicating the company is significantly exceeding its renewal targets, positive for customer retention and recurring revenue.

* Renewal Invoice Achvmnt %: 68.14% - A respectable rate for generating invoices from renewed policies, though not as high as policy achievement.

## 📈 Detailed Visual Analysis:

### 1] Overall Performance Summary (Top Section):

* Visually compares "Target," "Achieve," and "Invoice" values for "New," "Cross sell," and "Renewal" categories.

* For "New," "Achieve" (3.5M) and "Invoice" (0.8M) are significantly lower than "Target" (19.7M).

* For "Cross sell," "Achieve" (13.04M) is closer to "Target" (20.09M), but "Invoice" (3.04M) is much lower.

* For "Renewal," "Achieve" (18.51M) significantly surpasses "Target" (12.32M), and "Invoice" (8.39M) also shows strong performance.

* Provides an immediate visual representation of where the business is excelling (renewals) and where it is struggling (new and cross-sell invoice generation).

### 2] No Of Meeting By Account Executive:

* Shows the number of meetings conducted by each Account Executive.

* Gilbert leads with 61 meetings, followed by Ketan Jain (27) and Vidit Shah (27).

* Mark and Animesh Rawat also have significant meeting counts.

* The "Total Meeting Count" of 34 suggests an average or median.

* Indicates individual executive activity levels.

### 3] Top 4 Oppty By Revenue:

* Highlights the top four opportunities by revenue.

* "Fpe" accounts for 500K, "DB (Mega Po..." for 400K, and "EI-Group Ma..." for 400K.

* Helps in identifying the most lucrative opportunities currently in the pipeline.

### 4] Oppty - Product Distribution:

* A donut chart shows the distribution of opportunities by product type.

* "Marine" (49) and "Employee..." (49) represent the largest shares of opportunities.

* Other product types include Fire (2.1), Engineering (6), Liability (7), Terrorism (13), and Miscellane... (15).

* Indicates which products are generating the most interest or sales efforts.

### 5] No Of Invoice By Account Executive:

* Displays the number of invoices generated by each Account Executive.

* Abhinav Shivam and Abhirav Vinay have the highest number of invoices (7 and 5 respectively).

* Other executives like Animesh Rawat, Ketan Jain, and Gilbert also contribute.

* Helps assess the effectiveness of each executive in closing deals and generating revenue.

### 6] Top 4 Open Oppty By Revenue:

* Focuses specifically on open opportunities by revenue.

* "DB (Mega P..." and "EI-Group M..." both have 400K in open opportunities, while "CVP GMC" has 350K.

* Helps in pipeline management and forecasting.

### 7] Stage By Revenue:

* Shows revenue distribution across different sales stages.

* "Quality Opportun..." accounts for 592K, followed by "Negotiate" with 899K and "Propose Solution" with 99K.

* Provides insights into the health of the sales pipeline at various stages.

### 8] Total Oppty & Total Open Oppty:

* These two cards prominently display the total number of opportunities (49) and total open opportunities (44).

* Indicates that a large proportion of current opportunities are still active and not yet closed.

# ✅ Findings and Recommendations:

Renewal Success:

Finding: The exceptional performance in renewals (150.23% policy achievement) is a significant strength.

Recommendation: Continue to nurture existing client relationships and understand the factors contributing to this success to replicate best practices.

New Business and Cross-sell Challenges:

Finding: The low achievement rates for new policies and, more critically, for new and cross-sell invoices (4.21% and 15.14% respectively) highlight a major area for improvement.

Recommendation: Investigate bottlenecks in the sales-to-invoicing process for new and cross-sell business. This could involve process review, sales training on closing and paperwork, or improved coordination between sales and billing teams.

Executive Performance Discrepancies:

Finding: While Gilbert leads in meetings, his invoice contribution isn't explicitly highlighted as top. Conversely, Abhinav Shivam and Abhirav Vinay are strong in invoice generation.

Recommendation: Analyze the conversion rates from meetings to invoices for each executive. Provide targeted coaching or reallocate leads based on strengths in different stages of the sales cycle.

Opportunity Management:

Finding: With 44 out of 49 opportunities still open, there's a strong pipeline.

Recommendation: Focus on accelerating the progression of these open opportunities through the sales stages, particularly those with higher revenue potential identified in "Top 4 Open Oppty By Revenue."

Product Focus:

Finding: "Marine" and "Employee..." products are generating the most opportunities.

Recommendation: Explore if sales efforts are adequately aligned with these high-opportunity products and if there are opportunities to cross-sell or up-sell within these segments.

🧭 Interactivity

The dashboard includes several interactive elements:

Filters (Left Panel): "Year," "Stage," and "Employee Name" allow users to drill down and analyze data based on specific criteria.

Target/Achieve/Invoice Toggle (Below Cross-sell section): This likely allows users to switch the displayed values between target, achieved, and invoiced amounts for a more focused view.

🛠 Tools & Technologies Used

Power BI – for dashboard design, visualization, and interactivity.

Underlying Data Sources (specifically brokerage, fees, budget, invoice, meeting, opportunity tables) – for raw data storage.

DAX (Data Analysis Expressions) – likely used for creating calculated measures like achievement percentages and total opportunity counts.

# 📈 Skills Demonstrated

* Data Visualization

* KPI Development & Tracking

* Dashboard Design & Layout

* Sales Performance Analysis

* Opportunity Management Insights

* Renewal Rate Analysis

# 👨‍💻 Author

Karthik Gk
