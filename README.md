# p2p leanding risk control

**Task**

Thanks to your excellent Data Science skills, Dr. D. made a lot of money with his amazin' grocery store. He wants to invest that money smartly. To him, investing in the stock market does not seem so lucrative. A friend recently told Dr. D. that you can make tons of money in peer2peer lending.

Fascinated by the possibility to make even more money, Dr. D. decides to invest $10,000,000 in peer2peer lending on LendingClub.com (https://www.lendingclub.com/ Links to an external site.).

However, Dr. D. does not want to do so blindly! He heard that people can be late on their payments or even default on LendingClub.com. So he asks his Data Science team, YOU, to help him figure out where to invest his money.

To give you some data to work on, Dr. D. had asked someone to download nearly 30 million records from LendingClub.com (starting in 2007 and going all the way to 2018!). They are split into two files:

Accepted Loans (151 variables)
Rejected Loans (9 variables)


Given the comprehensive analysis conducted by our team on the LendingClub.com data, our strategic approach invloves investing in peer-to-peer lending, ensuring Dr. D maximizes his investment returns while minimizing risk.

**Data Processing:**

Our journey began with the meticulous examination of nearly 2 million records, encompassing both accepted and rejected loan applications from LendingClub.com spanning 2007 to 2018. The challenge lay in navigating through the vast sea of 151 variables within the accepted loans dataset and 9 variables for rejected loans. By employing data trimming techniques, we streamlined the accepted dataset to 16 core features that directly relate to loan and borrower reliability, enhancing computational efficiency and clarity.

**Strategic Insights through Advanced Analytics:**

The heart of our strategy revolves around leveraging these condensed datasets to unearth patterns and insights that dictate loan profitability. Through exploratory data analysis (EDA), we established a strong correlation between loan approval status and the Debt-to-Income (DTI) ratio, underscoring DTI's significance as a pivotal metric in loan assessment.

Stacking the two datasets on four shared features, We employed logistic regression, and our model achieved an impressive 98% accuracy in predicting loan status, with the DTI ratio emerging as the most influential feature, thereby guiding our investment strategy. This initial step put ourselves in the shoe of the lenders to relive how the loan decision was made in the first place.

We also found out changing the threshhold of the DTI is crucial for minimizing risk, if Dr. D wants to employ an overarching strategy that is based solely on DTI. We advise him to take granular approach. As shown on the DTI by loan status group chart, we spot that the concentrated occurence of fully paid applicants are around 15 percent DTI, while those chared off group that we want to minimize are around 20 percent DTI. Instead of taking a binary decision, Dr D could give those at 15 percent a favorable interest rate, while have those at 20 percent DTI to more stringent scrutiny.  

Further analysis is diverted on the accepted data by utilizing machine learning techniques, specifically XGBoost, compared against other tree-based methods like AdaBoost, Random Forest, and Decision Tree, and it revealed the most important features for loan profitability: DTI ratio, interest rate, and FICO score.

**LASSO Model - Sharpening Our Focus:**

The LASSO model played a critical role in refining our investment criteria, effectively selecting features that significantly impact loan profitability. It confirmed the paramount importance of investing in loans characterized as Grade A, with terms less than 36 months, and issued to borrowers with employment lengths between 1 to 10 years. Conversely, the model advised against investments in long-term loans (60 months), Grade D loans, and those issued to borrowers with high DTI ratios, aligning with our strategy to mitigate risk and focus on high-return loans.

**Conclusion - A Tailored Investment Strategy:**

Based on the comprehensive analysis and insights garnered through data science techniques, we recommend Dr. D. to adopt a strategic investment approach focusing on short-term, high-grade loans issued to mid-career professionals. This strategy not only aligns with the predictive insights derived from our sophisticated models but also positions Dr. D. to capitalize on the most lucrative opportunities within the peer-to-peer lending space, thereby maximizing his investment returns while mitigating risk.

This tailored approach, grounded in data-driven insights and validated through advanced analytics, equips Dr. D. with a robust investment strategy, ready to navigate the complexities of peer-to-peer lending and unlock the potential for substantial financial returns.
