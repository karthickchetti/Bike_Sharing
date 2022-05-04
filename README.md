# Bike_Sharing Case Study
**Objectives** : <br>
-This case study is performed to analyze the demand of the bikes for the bike sharing platform and analyze the impact of different variables affecting the demand for the bikes<br>
-Fitting a Multi-Linear regression model to predict the demand for the customers using important predictors based on its coefficients of linear regression model<br>

**Libraries Used** :<br>
-statsmodel.api<br>
-sklearn<br>
-pandas<br>

**Conclusion**
The linear regression model was fit on the data. The model metrics are :<br>
-Training Rsquared = `0.812`<br>
-Test Rsquared = `0.848`<br>

The equation of the best fit line is :
`cnt = 835.9 + 5015.1 * atemp + 2007.0 x yr + 1027.* winter + 75.4 * weekday - 2090.3 * light rain/snow - 812.6 * windspeed - 599.2 * holiday - 595.4 * misty`

**License**<br>
Use of this dataset in publications must be cited to the following publication:

[1] Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge", Progress in Artificial Intelligence (2013): pp. 1-15, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.

**Contact**<br>
For any questions related to the linear regression model, please feel free to contact *karthick120497@gmail.com*
