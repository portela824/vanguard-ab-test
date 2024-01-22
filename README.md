# Project 2

# Project objective

** Contex and Challenge: ** 
The digital world is evolving, and so are Vanguard’s clients. Vanguard believed that a more intuitive and modern User Interface (UI), coupled with timely in-context prompts (cues, messages, hints, or instructions provided to users directly within the context of their current task or action), could make the online process smoother for clients.The critical question was: 

** Would these changes encourage more clients to complete the process? **
 
# Methods
1. An A/B test was set:
  - ** Control Group **: Clients interacted with Vanguard’s traditional online process.
  - ** Test Group **: Clients experienced the new, spruced-up digital interface.
2. Perfomance Metrics 
3. Hypothesis Testing
 
# Technologies 
  - Python 3.9.18 
  - Jupyter Notebook 6.4.12
  - Tableau Public

  - Python libraries:
    1. pandas
    2. os
    3. matplotlib.pyplot
    4. seaborn
    5. numpy
    6. statistics
    7. statsmodels.api
    8. statsmodels.stats.proportion -proportions_ztest
    9. scipy.stats - ttest_ind
    10.sqlalchemy - create_engine

# Project Description

The dataset for this analysis comprises three distinct datasets that collectively offer a comprehensive view of client interactions and characteristics. The "Client Profiles" dataset (df_final_demo) encompasses crucial demographic information such as age, gender, and specific account details, providing a foundational understanding of the client base. The "Digital Footprints" dataset (df_final_web_data) delves into detailed client interactions online, bifurcated into two parts (pt_1 and pt_2). It is recommended to merge these files for a more comprehensive analysis of online behavior. The "Experiment Roster" dataset (df_final_experiment_clients) serves as a key component, revealing the clients involved in the grand experiment. In terms of performance metrics, the analysis focuses on key performance indicators (KPIs) such as completion rate, time spent on each step, and error rates. A pivotal hypothesis centers around the completion rate disparity between the Test and Control groups, where the Test group exhibits a higher completion rate. Statistical testing is employed to confirm the significance of this difference, considering the significance level, p-value, and other statistical measures. Additionally, a cost-effectiveness analysis is conducted, aligning with Vanguard's threshold of a minimum 5% increase in completion rate to justify the costs associated with the introduction of a new UI design. This multifaceted approach ensures a robust evaluation of the new design's success, encompassing statistical significance and cost-effectiveness considerations. Further exploration includes an examination of the average age of clients, allowing for a nuanced understanding of demographic dynamics in relation to the redesign's impact.

# Insights
  - Dataset inconsistency.
  - Difficulties with Tableau and calculation of the KPI's.
  - Analysis Results:
     1.Test results indicated differences between the variations.
     2.Upon visual inspection, no noticeable difference was observed.

# Conclusion
  To optimize the user experience, it is recommended to leverage the insights gained from the A/B test results. Given the slightly higher completion rate in the 'Test' variation, a detailed analysis of the design elements contributing to this improvement is crucial. Exploring the reasons behind the increased average time spent in the 'Test' variation can uncover a greater engagement and potential usability enhancements. Addressing NaN error rates is essential, to confirm the absence of critical issues or, conversely, understand why errors may not have been recorded. Additionally, a thorough evaluation of the cost-effectiveness of the redesign is necessary, considering the observed completion rate increase did not meet the 5% threshold. Tailoring marketing strategies based on the significant difference in average age between variations can enhance communication effectiveness. Continuous monitoring, iterative improvements, user segmentation, and a long-term impact assessment will collectively contribute to a comprehensive and effective strategy for sustained success.

# References
  data-bootcamp-v4. (2023). Lessons - 5_6_eda_inf_stats_tableau project. GitHub Repository. https://github.com/data-bootcamp-v4/lessons/tree/main/5_6_eda_inf_stats_tableau/project/files_for_project
