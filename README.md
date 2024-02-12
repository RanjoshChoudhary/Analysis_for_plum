# Analysis_for_plum
**OBJECTIVE:**
The data provided by PLUM company was analyzed to assess the efficiency of different groups within the organization in managing emails and tickets. This analysis aimed to identify patterns, efficiencies, and areas of improvement in ticket handling processes to enhance overall customer support performance.

**Exploratory Data Analysis Performed:**
1. Data Overview: Initial exploration of the dataset to understand its structure, including the number of rows/columns and column names.
2. Unique Groups Identification: Determination of unique departments (groups) handling tickets to understand the distribution of workload.
3. Status Distribution: Analysis of ticket statuses to gauge the resolution and pending rates.
4. Volume Analysis by Group: Evaluation of ticket volume by group to identify which departments are handling more tickets.
5. Priority Levels Identification: Identification of unique priority levels within the ticket data to understand the categorization of tickets based on urgency.

**Analysis Performed:**
1. **Ticket Distribution by Group**: Visualization of ticket distribution across different groups using bar and pie charts [Percentage Contribution of Each Group ] to illustrate workload distribution.
2. Resolution and Response Time Analysis: Calculation and comparison of average resolution and response times by group to identify efficiency and response effectiveness.
3. **Customer Satisfaction Score (CSAT) Calculation**: Analysis of customer satisfaction scores by converting them to numeric values, filtering out non-numeric ratings, and calculating the percentage of responses indicating satisfaction (scores of 4 or 5).
4. **Correlation Analysis**: Examination of the correlation between ticket priority and resolution time to statistically validate if higher priority tickets are resolved faster.
5. Average Resolution time per group over 10 weeks of Data [Trend] with Ticket Volume- Observing the lines for each group, you can identify trends in how efficiently each group resolves tickets over time. A downward trend in resolution time suggests improving efficiency, while an upward trend might indicate growing challenges or increasing complexity in tickets. By comparing the resolution times against the background of ticket volume (grey bars), you can infer the impact of workload on resolution efficiency.

**Based on the analysis conducted, the following insights were derived:**
- High Level of Customer Satisfaction: The calculation of the Customer Satisfaction Score (CSAT) revealed a high level of customer satisfaction i.e. **88.56 %** , indicating effective resolution processes and quality of service in addressing customer issues.
- Opportunity for Improvement in Communication: While the CSAT indicated high satisfaction, the analysis(high reopens of tickets in **Reimbursement claims** group) also pointed towards potential areas for improvement in communication and resolution times to further enhance customer satisfaction levels.
- Workload Visualization: The distribution of tickets among different groups was clearly visualized, revealing which departments are more heavily burdened with tickets, facilitating better resource allocation and workload balancing.(Despite handling a significant volume of tickets (as indicated by its large slice in the pie chart), this group has the **lowest average resolution time**. This suggests that the **Support group** is highly efficient, possibly due to streamlined processes, simpler issues, or effective resolution strategies.)
- Correlation Analysis: It was found that High-Priority Tickets are indeed being resolved faster than lower priority tickets.


**Conclusion:**
The Analysis Conducted in this notebook offers a comprehensive look into PLUM's ticket handling and customer satisfaction metrics. By focusing on the distribution of tickets across groups, the efficiency of resolution times, and the overall customer satisfaction levels, PLUM can identify strengths and areas for improvement within their customer support operations. The insights derived from this analysis underscore the importance of efficient ticket resolution processes and the impact they have on customer satisfaction. Moving forward, PLUM could leverage these findings to streamline operations, ensure resources are allocated effectively, and continue to enhance the quality of customer service, thereby maintaining or even improving the high levels of customer satisfaction already achieved. ​​
