# Supplemental Nutrition Assistance Program: Consumer Behavior Analysis with Python

# Background
SNAP provides food assistance to low-income households in the US. Despite concerns about food insecurity, SNAP households tend to spend a larger portion of their budget on unhealthy, hedonic food items. Studies have shown that SNAP participants purchase more sugary beverages, desserts, and snacks, which contribute to obesity and chronic diseases. Even after considering income and education, SNAP participants tend to have larger waists and higher obesity rates. However, the underlying psychological reasons for this behavior remain unknown. To address this gap, researchers conducted an online shopping study to explore the psychological mechanisms that drive SNAP households to buy more unhealthy food items.

# Recommendations to USDA Director regarding Supplemental Nutrition Assistance Program
Below, I present my recommendations on what the USDA should do to reduce SNAP households' unhealthy food consumption, supported by insights from academic papers:
1. Increase the pain of paying: The USDA should consider implementing measures to increase the pain of paying for SNAP households. Mandating store managers to distribute cash in envelopes instead of using electronic benefit transfer (EBT) cards or food stamps can enhance the perceived ownership of the cash and increase the sense of loss when making purchases. Studies have shown that the pain of paying reduces impulsive purchases, particularly for hedonic products. (Insights from 6.3 Module: Deliberate and Impulsive Purchase Decisions).
2. Utilize online store format: The USDA should promote online grocery shopping for SNAP households. Online grocery platforms can serve as a healthier alternative by reducing the consumption of vice products, including hedonic food items. Research suggests that online shopping diminishes the desire for instant gratification and leads to fewer impulsive purchases. By presenting products symbolically rather than physically, online channels decrease the vividness of vice products and enable consumers to make healthier choices. (Huyghe et al.).
3. Exposure to responsible and healthy brand associations before shopping: The USDA can expose SNAP households to brands that are linked to responsible and healthy characteristics. For example, they can collaborate with well-known brands that offer organic, locally sourced, or sustainably produced food products. By featuring these brands in educational materials, online platforms, or promotional campaigns, SNAP households can be exposed to the association between responsible choices and these reputable brands. Rebranding USDA and SNAP programs to emphasize responsible purchasing can prime SNAP households for making healthier food choices. Research has shown that exposure to goal-relevant brands influences behavior, and presenting SNAP households with brands associated with responsible choices may positively impact their decision-making. (Fitzsimons et al.).
4. Encourage shopper to eat before shopping or providing a sandwich prior to shopping: SNAP households can be advised to eat a meal before grocery shopping or provided with a complimentary healthy snack to reduce hunger-driven impulsive choices. Research has demonstrated that satiation through food consumption prior to shopping can help individuals adhere to their shopping lists and resist unplanned impulse purchases. (Bushong et al.). 

# Consumer Behavior (Attention, Coherence, and Emotion Framework)
Using the ACE framework, we can draw the following conclusions regarding the differences in metal processes underlying SNAP households’ food purchase decisions compared to non-SNAP households:
* Attention to hedonic food items. Both SNAP and non-SNAP households exhibit attention to hedonic food items, as indicated by their cravings for such food. However, SNAP households tend to have a higher level of craving for both hedonic and utilitarian food items compared to non-SNAP households. Given that we process information sequentially, it is reasonable to assume that SNAP households, due to their circumstances of food insecurity and financial constraints, may engage less in system 2 thinking (analytical and deliberative thinking) and rely more on system 1 thinking (heuristics or mental shortcuts) when making food choices. The heightened perceptibility and reliance on system 1 thinking may contribute to their higher levels of attention and craving for food items.
* Intensity of emotional responses varies between the two groups. SNAP households experience stronger cravings for both hedonic and utilitarian food items compared to non-SNAP households. This heightened emotional response can be attributed to the stressful situation SNAP households face, including food insecurity and lack of financial ability to afford food. The immediate need to make choices about acquiring or consuming food regardless of health benefits may lead SNAP households to prioritize immediate gratification.
* Coherence and its role in justifying hedonic purchases. Despite being aware of the potential negative health outcomes associated with indulging in hedonic food, SNAP households engage in implicit justifications to maintain coherence in their decision-making. This helps bridge the gap between their cravings and their beliefs about health, enabling them to find coherence and reconcile any cognitive dissonance that may arise. Our analysis reveals that SNAP households, on average, do not perceive hedonic foods as unhealthy as non-SNAP households, indicating a coherent mental process that aligns cravings with a lower perception of unhealthiness. This is further supported by the finding that SNAP households do not consider hedonic food to be better value for money compared to utilitarian food. The implicit justifications employed by SNAP households may stem from the need to maintain a sense of balance, satisfaction, and emotional well-being, even when making hedonic food choices.

# Summary Insights
These insights highlight the divergent consumption patterns, value perceptions, and food cravings between SNAP and non-SNAP households. The findings suggest that factors beyond income and education play a significant role in shaping the food choices of SNAP households. Further investigation is needed to identify the underlying factors influencing these differences and design targeted strategies to address the specific needs of SNAP households in terms of food preferences and consumption patterns.
1. Based on Figure 1's T-Test Results, there is a significant difference between the types of food purchased by SNAP and non-SNAP households. SNAP households tend to buy more hedonic products but fewer utilitarian products, with higher average values for both categories.
2. From the summary results of OLS regression in Figure 3, income and education are not statistically significant predictors of the consumption patterns of SNAP households, suggesting that other unexplored factors may play a more influential role.
3. According to the analysis in Figure 4, SNAP households do not consider hedonic food to be better value for money compared to utilitarian food.
4. The analysis in Figure 6 and Figure 7 reveals that SNAP and non-SNAP households' unhealthiness perceptions of food differ. SNAP households perceive both hedonic and utilitarian products as less unhealthy than non-SNAP households.
5. For hedonic food, craving differs between SNAP and non-SNAP households. SNAP households report higher craving levels for both hedonic and utilitarian products compared to non-SNAP households.
6. The relationship between craving and unhealthiness perception for hedonic food varies for SNAP and non-SNAP households. Craving has a stronger negative correlation with unhealthiness perception among SNAP households compared to non-SNAP households.

# Analysis
![Figure2](/images/Figure2.png)<br>
In summary, the results indicate that SNAP and non-SNAP households differ in terms of both the number and value of the food products they purchase. SNAP households tend to purchase a higher number of hedonic products but a lower number of utilitarian products compared to non-SNAP households. Additionally, SNAP households have a higher average value of both hedonic and utilitarian products compared to non-SNAP households. These findings provide insights into the divergent preferences and purchasing patterns of SNAP and non-SNAP households when it comes to food choices.

![Figure3](/images/Figure3.png)
![Figure4](/images/Figure4.png)<br>
Based on the statistical analysis results, the p-values for both income and education exceed the conventional significance level of 0.05 for all dependent variables. Therefore, income and education are not statistically significant predictors of the consumption patterns of SNAP households, and we fail to reject the null hypothesis. In other words, the results suggest that there is no statistically significant relationship between education or income and the consumption patterns of SNAP households. It is important to note that any observed associations between education or income and the dependent variables could be due to chance or random variation.

* Specifically, for the dependent variable "Number_HedonicProducts", neither income (p-value = 0.321) nor education (p-value = 0.209) demonstrate a significant relationship.
* Similarly, for "Number_UtilitarianProducts", both income (p-value = 0.307) and education (p-value = 0.336) do not have a statistically significant impact on the consumption pattern.
* The same lack of significance holds true for "Hedonic_Value" (income p-value = 0.233, education p-value = 0.183) and "Utilitarian_Value" (income p-value = 0.292, education p-value = 0.455).
* In this case, since the obtained p-values for the F-statistics are 0.361 and 0.284, which are both greater than the commonly used significance level of 0.05, we do not have sufficient evidence to conclude that income and education, as combined independent variables, significantly explain the consumption pattern of SNAP households.
  
Consequently, based on these findings, we cannot conclude that the consumption patterns of SNAP households can be solely explained by income and education. It is likely that other unexplored factors or variables play a more influential role in determining the consumption patterns of SNAP households. Further investigation is needed to identify these additional factors and understand their impact.


![Figure5](/images/Figure5.png)<br>
Based on the analysis of the data, including the results of the t-test and OLS regression, it can be concluded that no, SNAP households do not consider hedonic food to be better value for money compared to utilitarian food.

**T-Test Results:**
* The average P-value rating for Hedonic Products is 2.929, while the average P-value rating for Utilitarian Products is 2.997. The t-statistic is -0.601 with a p-value of 0.549. A low p-value in the t-test indicates that there is no significant difference in the perceived value for money between hedonic and utilitarian products for SNAP households. In other words, the difference in the average P-value ratings is likely due to random chance, rather than a meaningful difference in value perception.

**OLS Regression Results:**
* The F-statistic is 3.822 with a p-value of 0.000232. This suggests that the overall regression model is statistically significant, indicating that the independent variables collectively have an impact on the dependent variable (Hedonic_Value). However, when examining the individual independent variables, we find that none of them have statistically significant coefficients (p-values > 0.05). This means that the independent variables, including variables related to perceived value (Pvalue_Hedonic and Pvalue_Utilitarian), do not have a significant impact on the dependent variable. Therefore, we cannot conclude that SNAP households consider hedonic food to be better value for money than utilitarian food based on the results of the regression analysis.

![Figure6](/images/Figure6.png)<br>
Based on the results, it is evident that SNAP households' unhealthiness perceptions of food differ from non-SNAP households.

**For Hedonic products:**
* The average unhealthiness rating for SNAP households is 4.087, whereas for non-SNAP households it is 4.671. This suggests that non-SNAP households perceive Hedonic products to be slightly more unhealthy compared to SNAP households.
The t-statistic is -9.098 with a remarkably low p-value of 4.858e-19. This indicates a statistically significant difference in unhealthiness perceptions between the two groups.

**For Utilitarian products:**
* The average unhealthiness rating for SNAP households is 1.614, while for non-SNAP households it is 1.498. This implies that non-SNAP households perceive Utilitarian products to be slightly more unhealthy than SNAP households do.
* The t-statistic is 2.606 with a p-value of 0.0093. This suggests a statistically significant difference in unhealthiness perceptions between the two groups.
* The results of the t-tests confirm that there is a significant disparity in unhealthiness perceptions between SNAP and non-SNAP households for both Hedonic and Utilitarian products. SNAP households tend to perceive Hedonic products as less unhealthy, while non-SNAP households perceive them as more unhealthy. Similarly, SNAP households perceive Utilitarian products as slightly less unhealthy compared to non-SNAP households.

These findings support the notion that SNAP households' unhealthiness perceptions of food differ from those of non-SNAP households. The disparities may arise from variations in factors such as socioeconomic status, dietary preferences, or cultural influences.

![Figure7](/images/Figure7.png)<br>
Based on the results of the t-test analysis and the comparison of craving ratings between SNAP and non-SNAP households, it can be concluded that SNAP households' reports of food craving differ from non-SNAP households.

**For Hedonic Products:**
* SNAP households reported an average craving rating of 3.030, while non-SNAP households reported an average rating of 2.622.
The t-statistic for the comparison of craving ratings between SNAP and non-SNAP households was 4.552, with a p-value of 5.974e-06.
These results indicate a statistically significant difference in craving ratings for Hedonic Products between the two groups. SNAP households, on average, reported higher craving levels for Hedonic Products compared to non-SNAP households.

**For Utilitarian Products:**
* SNAP households reported an average craving rating of 2.582, while non-SNAP households reported an average rating of 2.154.
The t-statistic for the comparison of craving ratings between SNAP and non-SNAP households was 5.095, with a p-value of 4.158e-07.
Similar to Hedonic Products, there is a statistically significant difference in craving ratings for Utilitarian Products between SNAP and non-SNAP households. SNAP households, on average, reported higher craving levels for Utilitarian Products compared to non-SNAP households.

These findings suggest that SNAP households experience stronger cravings for both Hedonic and Utilitarian food items compared to non-SNAP households. The results indicate that food craving is influenced by household type, with SNAP households exhibiting higher levels of craving across both food categories.

![Figure8](/images/Figure8.png)
![Figure9](/images/Figure9.png)<br>
The results reveal that there is a correlation between craving and unhealthiness perception. Furthermore, the relationship between craving and unhealthiness perception varies for SNAP and non-SNAP households.

**Based on the results:**
* _Correlation_: For SNAP households, there is a moderate negative correlation (-0.508) between craving for hedonic food and perceptions of its unhealthiness. This indicates that as craving increases, the perception of unhealthiness decreases. However, for non-SNAP households, there is a weak negative correlation (-0.077) between craving and unhealthiness perception.
* _Regression Analysis - SNAP Households_: The regression analysis shows that craving for hedonic food is a statistically significant predictor of unhealthiness perception for SNAP households (p < 0.001). The R-squared value of 0.255 indicates that craving explains about 25.5% of the variation in unhealthiness perception among SNAP households.
* _Regression Analysis - Non-SNAP Households_: The regression analysis for non-SNAP households also shows that craving for hedonic food is a statistically significant predictor of unhealthiness perception (p < 0.001). However, the R-squared value is much lower (0.015), indicating that craving explains only 1.5% of the variation in unhealthiness perception among non-SNAP households.

In summary, there is a stronger negative relationship between craving for hedonic food and perceptions of its unhealthiness among SNAP households compared to non-SNAP households. Craving is a more significant predictor of unhealthiness perception for SNAP households.

# Works Cited
* Bushong, Benjamin, et al. “Pavlovian Processes in Consumer Choice: The Physical Presence of a Good Increases Willingness-to-Pay.” American Economic Review, vol. 100, no. 4, Sept. 2010, pp. 1556–71. EBSCOhost, https://doi-org.proxy.library.cornell.edu/10.1257/aer.100.4.1556.
* Fitzsimons, Grainne M., et al. “Automatic Effects of Brand Exposure on Motivated Behavior: How Apple Makes You ‘Think Different.’” Journal of Consumer Research, vol. 35, no. 1, June 2008, pp. 21–35. EBSCOhost, https://doi-org.proxy.library.cornell.edu/10.1086/527269.
* Huyghe, Elke, et al. “Clicks as a Healthy Alternative to Bricks: How Online Grocery Shopping Reduces Vice Purchases.” Journal of Marketing Research (JMR), vol. 54, no. 1, Feb. 2017, pp. 61–74. EBSCOhost, https://doi-org.proxy.library.cornell.edu/10.1509/jmr.14.0490.
