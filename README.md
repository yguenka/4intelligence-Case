<img src="Fotos/0.jfif">

<h1><b><p align="center">Data Analysis Skill Test</p></b></h1>
<p align="justify">There are 2 cases developed for the selection process of 4 intelligences for Data Scientist in this repositor.</p>

<h2>CASE 1</h2>
<p align="justify">Using `TFP.csv`:</p>
<ol>
<h3><li><b>Make an exploratory data analysis</b></li></h3>
<dt>First, I did country data analysis as the image below.</dt>
<p align="center"><img src="Fotos/Capturar1.JPG"></p>
<dt>And in the next figure, there’s a plot by country to know if the data has any frequency.</dt>
<p align="center"><img src="Fotos/Capturar2.JPG"></p>
<dt><b>When we analyse both pictures, we can conclude that Canada has a higher frequency value than other countries.
</b></dt>



<h3><li><b>Forecast 10 years of the series</b></li></h3>
<dt><p align="justify">The graph below shows whether there is a relationship between the previous period and the following period. They are divided by countries too: USA, CAN, MEX respectively.</p></dt>
<p align="center"><img src="Fotos/Capturar3.JPG"></p>

<dt><p align="justify"><b>The more aligned the points are means that more related they are. So we can say that among the 3 countries, the USA has a greater relationship between the following period and the previous period.</b></p></dt>

<h3><b>Forecast - USA</b></h3>
<dt><p align="justify">The figure below shows the lollipop chart. In it, we can see that the lollipop number 6 goes into the range. So let's use number 6 as a repetition period for the forecast.</p></dt>
<p align="center"><img src="Fotos/Capturar4.JPG"></p>
<dt><p align="justify">Descomposing a Time Series into: Mean, Trends, Seasonal Effects and Noise, we can see that both the trend and the observed value have a similarity, in additioin to having a sasonality, even with the residual value having a hight variation.</p></dt>
<p align="center"><img src="Fotos/Capturar5.JPG"></p>
<dt><p align="justify">Finally, we found a 10 year forecast from the USA in chart below. It is possible to observe that there is a small variation for forecast.</p></dt>
<p align="center"><img src="Fotos/Capturar6.JPG"></p>

<h3><b>Forecast - CAN</b></h3>
<dt><p align="justify">Differente from the USA, in CAN we can see that the lollipop number 4 goes into the range. So let's use number 4 as a repetition period for the forecast.</p></dt>
<p align="center"><img src="Fotos/Capturar7.JPG"></p>
<dt><p align="justify">Descomposing a Time Series into: Mean, Trends, Seasonal Effects and Noise, the trend and observed lines were also similar, in addition to a high sasonality. In the residual graph, we can observe a high variation in the early years and a smaller variation in the other years.</p></dt>
<p align="center"><img src="Fotos/Capturar8.JPG"></p>
<dt><p align="justify">As it can analyze at the graph, the variation seems quite large, but the forecast for 2018 is 0.974086 and for 2019 it is 1.002181.</p></dt>
<p align="center"><img src="Fotos/Capturar9.JPG"></p>

<h3><b>Forecast - MEX</b></h3>
<dt><p align="justify">In the case to MEX, we can see that the lollipop number 5 goes into the range. So let's use number 5 as a repetition period for the forecast.</p></dt>
<p align="center"><img src="Fotos/Capturar10.JPG"></p>
<dt><p align="justify">Descomposing a Time Series into: Mean, Trends, Seasonal Effects and Noise, the trend and observed lines were also similar, in additiom to a high sasonality like CAN. In the residual graph, we can notice a high variation like USA.</p></dt>
<p align="center"><img src="Fotos/Capturar11.JPG"></p>
<dt><p align="justify">Similar to CAN forecast, the variation seems quite large, but the forecast for 2018 is 0.964114 and for 2019 it is 0.998557.</p></dt>
<p align="center"><img src="Fotos/Capturar12.JPG"></p>

<h3><b>FORECAST  - 10 years</b></h3>
<p align="center"><img src="Fotos/Capturar13.JPG"></p>
<dt><p align="justify"><b>This is the forecast graph with the 3 countries. We can notice a high similarity between MEX and CAN.</b></p></dt>



<h3><li><b>Can you think about another feature that could be helpful in explaning TFP series? Explain</b></li></h3>
<dt><p align="justify">The TFP is a measure of residue, that is, it's the portion of the product not explained by physical capital, human capital and the amount of hours worked. For example, in years when the return to work goes up, the productivity component increases, which increases the factors and, for a given product level, reduces the PTF.

Then we can use the following geatures to calculate the TFP:<br />
<b>rgdpna</b>:Real GDP at constant 2005 national prices (in million 2005 USD).<br />
<b>rkna</b>:Capital stock at constant 2005 national prices (in million 2005 USD).<br />
like the following formula:<br />
<h3><p align="center"><b>TFP = rgdpna/rkna</b></p></h3>

</p></dt>
</ol>





<h2>CASE 2</h2>
<ol>
<h3><li><b>Show the evolution of total monthly and total annual exports from Brazil (all states and to everywhere) of ‘soybeans’, ‘soybean oil’ and ‘soybean meal’</b></li></h3>
<h3><b>Evolution of Total Monthly</b></h3>
<dt><p align="justify">By placing the graphs on the side, we can see that the product scale is very similar if you are not careful to see the y-axis in which there is a big difference in the amount of soybeans and soybean meal.</p></dt>
<p align="center"><img src="Fotos/Capturar14.JPG"></p>
<dt><p align="justify">But when placing on the same scale, it is possible to observe the difference in quantity between the products.</p></dt>
<p align="center"><img src="Fotos/Capturar15.JPG"></p>

<h3><b>Evolution of Total Annual</b></h3>
<dt><p align="justify">For annual values, we can observe an increasing curve for soybeans and for soybeans meal, different from soybean oil.</p></dt>
<p align="center"><img src="Fotos/Capturar16.JPG"></p>
<dt><p align="justify">When placed on the same scale, it's' difficult to visualize the drop in soybean oil exports.</p></dt>
<p align="center"><img src="Fotos/Capturar17.JPG"></p>



<h3><li><b>What are the 3 most important products exported by Brazil in the last 5 years?</b></li></h3>
<dt><p align="justify">The 3 most important products exported by Brazil in the last 5 years is <b>soybeans, corn and sugar</b>.</p></dt>
<p align="center"><img src="Fotos/Capturar18.JPG"></p>



<h3><li><b>What are the main routes through which Brazil have been exporting ‘corn’ in the last few years? Are there differences in the relative importance of routes depending on the product?</b></li></h3>
<dt><p align="justify">The main routes through which Brazil have been exporting 'corn' in the last few years is <b>sea</b>.</p>
<p align="center"><img src="Fotos/Capturar19.JPG"></p>

<dt><p align="justify"><b>We can oberved that all products are transporter products by sea.</b></p></dt>
<p align="center"><img src="Fotos/Capturar20.JPG"></p>



<h3><li><b>Which countries have been the most important trade partners for Brazil in terms of ‘corn’ and ‘sugar’ in the last 3 years?</b></li></h3>
<dt><p align="justify"><b>In the case of corn, the most important countries are Iran, Vietnam and Japan. For sugar, the most important contries are India, Bangladesh and Algeria. And ehen adding the two products, the most importante countries ate China, Iran and United arab Emirates.</b></p></dt>
<p align="center"><img src="Fotos/Capturar21.JPG"></p>



<h3><li><b>For each of the products in the dataset, show the 5 most important states in terms of exports?</b></li></h3>
<dt><p align="justify"><b>
Corn: MT, PR, GO, MS and SP

Sugar: SP, PR, MG, AL and MS

Soybean Meal: PR, MT, RS, GO and BA

Soybean Oil: PR, RS, MT, SC and GO

Soybeans: RS, MT, PR, GO and SP

Wheat: RS, PR, SC, SP and MS
</b></p></dt>
<p align="center"><img src="Fotos/Capturar22.JPG"></p>
<p align="center"><img src="Fotos/Capturar23.JPG"></p>



<h3><li><b>What should be the total brazilian soybeans, soybean_meal, and corn export forecasts, in tons, for the next 11 years (2020-2030)? We’re mostly interested in the annual forecast.</b></li></h3>
<dt><p align="justify">When analyzing the 3 lag plots, we can see the soybeans has a greater relationship between the previous period and the later period than the other products</p></dt>
<p align="center"><img src="Fotos/Capturar24.JPG"></p>

<h3><b>Forecast - Corn</b></h3>
<dt><p align="justify">We can see that the lollipop number 2 goes into the range. So let's use number 2 as a repetition period for the forecast.</p></dt>
<p align="center"><img src="Fotos/Capturar25.JPG"></p>
<dt><p align="justify">Descomposing a Time Series into: Mean, Trends, Seasonal Effects and Noise, we can see that both the trend and the observed value have a similarity, in additioin to having a sasonality, even with the residual value having a high variation in the final years.</p></dt>
<p align="center"><img src="Fotos/Capturar26.JPG"></p>
<dt><p align="justify">The next graph shows the forecast fot the next 11 years of corn.</p></dt>
<p align="center"><img src="Fotos/Capturar27.JPG"></p>

<h3><b>Forecast - Soybeans</b></h3>
<dt><p align="justify">The lollipop number 3 goes into the range. So let's use number 3 as a repetition period for the forecast.</p></dt>
<p align="center"><img src="Fotos/Capturar28.JPG"></p>
<dt><p align="justify">Descomposing a Time Series into: Mean, Trends, Seasonal Effects and Noise, we can see that both the trend and the observed a increasing value, even with the residual value having a high variation in the final years.</p></dt>
<p align="center"><img src="Fotos/Capturar29.JPG"></p>
<dt><p align="justify">The next graph shows the forecast fot the next 11 years of soybeans. We can see that there is a great variation in the values over the forecast.</p></dt>
<p align="center"><img src="Fotos/Capturar30.JPG"></p>

<h3><b>Forecast - Soybeans Meal</b></h3>
<dt><p align="justify">The lollipop number 3 goes into the range. So let's use number 3 as a repetition period for the forecast equal of seabeans.</p></dt>
<p align="center"><img src="Fotos/Capturar31.JPG"></p>
<dt><p align="justify">Descomposing a Time Series into: Mean, Trends, Seasonal Effects and Noise, we can see that both the trend and the observed a increasing value, even with the residual value having a high variation in the final years, equal of seabeans too.</p></dt>
<p align="center"><img src="Fotos/Capturar32.JPG"></p>
<dt><p align="justify">The next graph shows the forecast fot the next 11 years of soybean meal. We can see that there is a great variation in the values over the forecast.</p></dt>
<p align="center"><img src="Fotos/Capturar33.JPG"></p>

<h3><b>FORECAST  - 11 years</b></h3>
<dt><p align="justify"><b>This is the forecast graph with the 3 products. We can notice a high similarity between corn and soybean meal.</b></p></dt>
<p align="center"><img src="Fotos/Capturar34.JPG"></p>
<dt><p align="justify"><b>But by placing the graphic side by side, we can see that the 3 products follow an increasing line.</b></p></dt>
<p align="center"><img src="Fotos/Capturar35.JPG"></p>
</ol>