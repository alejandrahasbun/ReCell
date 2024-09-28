ReCell Project 

ReCell aims to develop a dynamic pricing strategy for used and refurbished phones and tablets by building a linear regression model. 
The model predicts the price of devices based on various features like screen size, RAM, camera quality, and days used, helping to optimize pricing strategies in a growing second-hand market.

Key Insights

Selfie Camera Impact: Adding the selfie_camera_mp variable significantly improved model accuracy, increasing the variance explained and reducing the mean squared error.
Residual Normality: The large sample size led to deviations from normal residual distribution, but the linear regression model remained robust.
Multicollinearity: Persistent multicollinearity between battery and screen_size makes their individual contributions harder to interpret, but they remain important predictors.

Recommendations

Competitive Benchmarking: Regularly benchmark your pricing against competitors to stay competitive while maintaining profitability.
Promote Eco-Friendly Pricing: Highlight the environmental benefits of buying used devices and offer eco-friendly pricing incentives.
Cross-Sell & Upsell: Showcase advantages of higher-priced models, like better cameras or larger screens, to encourage cross-selling and upselling.

Libraries Used

numpy 
pandas
matplotlib.pyplot
seaborn
scipy.stats
