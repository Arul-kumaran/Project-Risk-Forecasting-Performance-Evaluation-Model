# Project-Risk-Forecasting-Performance-Evaluation-Model

🔹 Introduction

Project risks and delivery failures are major challenges in project management and often result in cost overruns, schedule delays, and performance issues. This project uses data analytics techniques to analyze historical project data and identify the key factors that contribute to High and Critical project risks, enabling organizations to take early preventive actions and improve overall project success.

🔹 Dataset

The dataset used in this project consists of project-related records containing attributes such as project budget, team size, complexity score, schedule pressure, vendor reliability, methodology, project type, project start month, and risk level. It includes financial, operational, and risk-related information that helps in understanding project performance and risk behavior across different types of projects.

🔹 Process Followed

The analysis began with data loading and overview using Pandas to understand the dataset structure, dimensions, and data types. This was followed by data cleaning and preprocessing, which involved handling missing values, correcting data types, removing duplicates, standardizing categorical values, and creating derived columns such as budget category, team size range, complexity category, and budget per team member. Exploratory Data Analysis (EDA) was then performed using univariate, bivariate, and multivariate analysis to identify relationships between project attributes and risk levels. Groupby operations, pivot tables, and correlation analysis were used along with visualizations such as bar charts, box plots, scatter plots, line charts, and heatmaps to extract meaningful insights.

🔹 Visualization Techniques

Various visualization techniques were used to clearly present project risk patterns, including stacked bar charts, grouped bar charts, box plots, line charts, scatter plots, and heatmaps. These visualizations helped in comparing risk levels across complexity categories, budgets, team sizes, project types, and timelines, making the findings easy to understand for stakeholders.

🔹 Insights

The analysis showed that high project complexity significantly increases the likelihood of High and Critical risk. Projects with large budgets and large teams tend to have higher risk due to increased coordination challenges and financial exposure. High schedule pressure was found to be a strong contributor to project escalation, while poor vendor reliability further increased the chances of delivery failure. Risk levels were observed to be highest when multiple factors such as complexity, budget, and schedule pressure occurred together.

🔹 Recommendations

Based on the insights, several recommendations were proposed, including assigning experienced teams and project managers to high-complexity projects, enforcing strict monitoring for large-budget initiatives, reducing schedule pressure through realistic planning, strengthening vendor performance management, improving communication in large teams, and implementing a predictive risk scoring approach during project initiation to identify high-risk projects early.

🔹 Conclusion

This project demonstrates a complete data analytics workflow from data cleaning and exploratory analysis to visualization, insight generation, and recommendations. The findings help organizations proactively identify risky projects, improve planning and governance, and enhance overall project performance using data-driven decision-making.
