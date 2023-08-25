# sales_group_project
1. univariate category-wise sales analysis for a particular store (5 stores) - 44,
    1.1 inter category (auto, babycare) trend analysis for a store
        1.1.1 for each category we can test the presence of components.
        1.1.2 forecast of each category for the next 15 days - ARIMA, SARIMA, DL
        1.1.3 notice whether any two categories are showing any dependence in terms of sales (can offer a discount)
        1.1.4 
2. Cluster-based analysis take 2 or 3 clusters)
    2.1 within cluster
        2.1.1 for each category we can plot line chart for different stores in a cluster and see how is that category 
              sales varying within the same cluster but different stores, if the difference is not significant we can say
              that the sales are distributed homogenously within clusters for that category.
    2.2 among cluster
3. Multivariate Analysis - covariates like oil price, holidays will be used
    3.1 OIL PRICE
        3.1.1 for 5 stores we will check the impact of oil price on sales of each category, if there seems to be a 
              particular relation in terms of sales of any category and oil price we will infer that oil price is 
              affecting that category(and give real world reasons for that). - scatter plot of sales and oil price wrt 
              time.
        3.1.2 We can then based on oil, forecast the sales for those categories where oil seems to play a major role.
    3.2 HOLIDAYS
        3.2.1 [to be done on each of the 5 stores] According to different types of holidays we will check 
              3.2.1.1 whether each category sales is showing some changes, if yes then highlight it for further analysis
                      as done for oil prices.
        3.2.2 for each cluster perform the same analysis of whether sales are getting impacted by regional holidays or not.
              3.2.2.1 [if cluster show homogenous behavior in sales] Cluster wise see whether holiday are impacting sales 
                      of each cluster. 
    3.3 Checking whether holidays and oil prices have any dependence or not(most probably they won't) (get the total sales
        of for days of regional, local holidays etc and no holiday days and see whether there is a hike in sales or not 
        during holidays.)

Things to work on:
1. Forecast branch -
    1.1 ARIMA/SARIMA
    1.2 Deep learnng models
