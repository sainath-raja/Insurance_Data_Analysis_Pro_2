# Insurance_Data_Analysis_Pro_2

# InsuranceData-Dashboard

## 1. Project Title / Headline  
🛡️ Insurance Intelligence: Policy & Claims Analytics Dashboard  
A powerful and interactive Power BI dashboard built to explore insurance policy, premium, and claim trends using Microsoft SQL Server as the data source. This solution provides a full-scale visualization of customer policy behavior, gender insights, and feedback-driven service refinement.

---

## 2. Short Description / Purpose  
Insurance Intelligence is a comprehensive dashboard created by integrating SQL Server with Power BI to uncover insights from insurance policy and claims data. The dashboard enables deep exploration of premiums, claims, and customer behavior across various policy types, age groups, and feedback sentiments.

---

## 3. Tech Stack  
The dashboard was built using the following tools and technologies:<br>  
• 🗄️ **Microsoft SQL Server** – Used as the primary data source to store and manage the `InsuranceData.csv` dataset.<br>  
• 📊 **Power BI Desktop** – Used to build visuals, slicers, matrix, and card views for analysis.<br>  
• 🔁 **Scheduled Refresh** – Implemented in Power BI Service for daily/weekly data updates.<br>  
• 📤 **Power BI Service** – For publishing the report and enabling collaboration.<br>  
• 🧠 **DAX** – Used for dynamic KPIs, column creation (Active/Inactive customers), and conditional logic.<br>  
• 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews.

---

## 4. Data Source  
**Source:** `InsuranceData.csv` loaded into Microsoft SQL Server and connected to Power BI.

The dataset includes the following columns:<br>
• Policy Number<br>
• Customer ID<br>
• Gender<br>
• Age<br>
• Policy Type<br>
• Policy Start Date<br>
• Policy End Date<br>
• Premium Amount<br>
• Coverage Amount<br>
• Claim Number<br>
• Claim Date<br>
• Claim Amount<br>

Additionally, a new derived column for **Customer Status** (Active/Inactive) was created to enhance segmentation.

Another data source called `insurance_customer_feedback` was used for analyzing textual feedback.

---

## 5. Features / Highlights  

• **Business Problem**  
Insurance companies face challenges in monitoring and visualizing policy activity, gender trends, and claim settlement patterns. They also lack tools to gain actionable insights from customer feedback.

Key questions such as:  
- Which policies are most common among different age groups?  
- What is the trend of claim settlements by policy type?  
- How does customer sentiment relate to claim behavior?  

… are not easily answerable using raw tabular data.

---

• **Goal of the Dashboard**  
To develop an interactive dashboard that:  
- Connects directly to SQL Server for dynamic data access.  
- Helps users understand claim trends, gender insights, and premium patterns.  
- Visualizes customer sentiment and integrates it into business insights.

---

• **Walkthrough of Key Visuals**

📄 **Page 1: Policy & Claim Analysis**  
- Slicers for Claim Number, Policy Number, and Customer ID.  
- Card visuals for Total Premium, Coverage Amount, and Claim Amount.  
- Multi-row card visuals for customer gender breakdown.  
- Ribbon chart to show number of claims by Claim Status.  
- Bar and Line charts for Premium Amount by Policy Type and Claim Amount by Age Group.  
- Donut chart showing Active vs. Inactive Customers (based on derived column).  
- Matrix visual showing breakdown by Policy Type and Claim Status (Pending, Settled, Rejected).

📄 **Page 2: Drillthrough Table View**  
- Tabular view of all dataset columns to support Drillthrough filters on any record or combination of fields.

📄 **Page 3: Customer Feedback Analysis**  
- Visuals created from `insurance_customer_feedback` dataset.  
- Word Cloud for customer comment highlights.  
- Bar chart for feedback sentiment scores.  
- Matrix visual to map customer IDs with their corresponding feedback summaries.

---

• **Business Impact & Insights**

• Claims Insight: Track and compare claim statuses for better resolution trends.  
• Policy Optimization: Visualize policy popularity and premium distribution by age and gender.  
• Customer Segmentation: Identify and target active vs. inactive users.  
• Feedback Analysis: Use sentiment-driven visuals for service improvement and strategy.  
• Operational Efficiency: Drillthrough functionality simplifies data traceability and reporting.

---

## 6. Screenshots / Demos  
Show what the dashboard looks like.  
- ![Policy Overview](https://github.com/yourusername/repo/assets/policy_dashboard.png)  
- ![Claim Trends](https://github.com/yourusername/repo/assets/claim_visuals.png)  
- ![Feedback Word Cloud](https://github.com/yourusername/repo/assets/feedback_analysis.png)
