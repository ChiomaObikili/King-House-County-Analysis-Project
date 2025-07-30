<h1>King House County Analysis Project</h1>
<h2>Description</h2>
In this case study, I focused on predicting house sale prices within King County, Washington to identify key factors influencing house prices and uncover market trends using exploratory analysis, regression, and time series decomposition.
<h2>Goal</h2>
To analyze housing data from King County, Washington, and build a predictive model to identify key factors influencing home prices—ultimately helping buyers, sellers, and real estate analysts make informed decisions.
<h2>Context & Duration</h2>
This was a 4-week end-to-end capstone project completed during the machine learning phase of my data analytics certification. It combined statistical modeling, exploratory analysis, and geospatial visualization.
<h2>My Role</h2>
Lead Data Analyst – I conducted the entire analysis pipeline from data wrangling to modeling, visualization, and insights presentation using Python and Tableau.
<h2>Data Source</h2>
Kaggle (King County House Sales Dataset)
<h2>Tools Used</h2>
Python (Pandas, NumPy, Seaborn, Matplotlib), Machine Learning (Regression, Clustering), Folium (Geospatial), Tableau (Presentation).
<h2>Steps Taken</h2>
I cleaned and transformed raw housing data using Python.
Performed exploratory data analysis (EDA) to identify variable relationships.
Built regression models to quantify the impact of features like square footage,                                                                                         grade, and waterfront status.
Conducted clustering analysis to detect potential buyer segments.
Used time series decomposition to evaluate market trends.
Created geospatial maps to explore neighborhood-level price patterns.

<h2>Key Challenges and Solution</h2>
Challenge: Sparse pricing clusters made segmentation difficult so I used visual inspection and regression instead of relying solely on clustering.

<h2>Analysis and Result</h2>
As part of my analysis, I looked at how a home’s size (Sqft_Living) and quality rating (Grade) affected its sale price. I used scatterplots and a basic trendline to explore these relationships.The results showed a clear pattern: homes with more living space and higher quality ratings sold for more money. The upward trend in the chart made it easy to see—when size or grade went up, the price usually went up too.This told me that buyers care a lot about how big a home is and how well it’s built or designed. These two features stood out as important factors for predicting house prices and gave me a better idea of what really drives value in the housing market.


  
<img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/f62757e1-0415-4b99-a730-0cd06fdc4d77" /> <img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/6a825489-b268-46a0-b085-6a48c7963d97" />




When I looked at how the number of bedrooms and the above-ground square footage (sqft_above) affected house prices, I noticed a clear upward trend. Homes with more bedrooms or larger above-ground space tended to sell for more. This makes sense—bigger homes with more rooms usually have higher value.The regression line on the chart confirmed this pattern, showing a steady increase in price as these features grew. While there was some variation in the data—likely due to other factors like location or condition—the overall trend stayed consistent. This helped highlight that both bedroom count and sqft_above are important factors that influence how much a home is worth.



<img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/eae1ddda-23f6-4fc5-8755-5f16f7213b52" /> <img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/86d1df16-6e1d-478d-bb0a-a8bdb96a526d" />



I explored how the number of floors and waterfront views relate to house prices. For the number of floors, the chart showed a slight upward trend in the fitted line, but the data points were widely scattered. This means there’s no strong linear connection—having more floors doesn’t clearly predict a higher price.In contrast, homes with waterfront views stood out. Almost all of the highest-priced homes had a waterfront view, even though this isn’t a linear trend. Instead, it’s a strong categorical effect—just having a waterfront view (marked as 1) tends to raise the price significantly, compared to homes without one.



<img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/6b069b69-8cbb-4ff3-9d0f-a0f458e2bd6a" /> <img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/9ece0f71-a7df-4eed-9cd2-3d38096d77b1" />



Looking at the map, we can see that high-priced homes are spread across many areas, followed by medium- and low-priced homes. This shows that house prices vary by neighborhood, but most homes fall into the high price range.The map also suggests that a home’s value is not directly affected by the prices of nearby homes. Instead, factors like square footage, condition, quality (grade), and available features or amenities seem to have a much bigger impact on price.



<img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/9055ee4f-8670-468d-a71e-f7cb414f6d4d" /> <img width="450" height="400" alt="image" src="https://github.com/user-attachments/assets/a3e01320-6f83-4756-8cd6-6dd2cf31967c" />




<h2>Insights on Clustering Analysis</h2>
As part of my analysis, I looked at how features like bedrooms, sqft_living, and sqft_above relate to house prices. I wanted to see if the data naturally grouped into clusters—such as types of homes or buyer segments—but no clear clusters appeared. This means that in King County, house prices likely follow a continuous range, rather than falling into distinct categories.
However, one trend was very clear: as bedrooms, living space, and above-ground square footage increased, so did house prices. This supports earlier findings from the regression analysis and shows that these features are strong predictors of a home’s value—even if they don't divide the market into groups.


<h2>Recommendations</h2>

For Sellers
Focus on promoting key features like home quality (grade), square footage, or waterfront views, instead of just the number of bedrooms.


For Buyers
Don’t assume the neighborhood sets the price – A home’s value depends more on its own features (like size and condition) than on the price of nearby homes.
