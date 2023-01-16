
<h1>Can political regimes correlate differently with the economic growth of the country?</h1>
<p align="justify">
Economists do not have a consensus on that matter. Opponents of that theory say that for development, primary stability is needed, and democracy institutions are too breakable. For example, the fast economic growth of China, Japan and other Asian countries are explained by that. Democratic leaders can sacrifice the interest of economic growth to satisfy the needs of low-income groups, while autocratic regimes can maintain unpopular economic policies. To conclude, developing countries simply cannot afford such good democracy to develop.

Supporters of that theory insist that autocratic regimes are too dependent on the personality of the country leader. The ways they try to keep power makes them inefficient and they lack the information necessary for the decision-making process, which leads to worse management. What makes democracy better regime for economic growth, it is protection of human life (i.e. human capital, which is necessary for economic growth).
</p>

<h3>Hypothesis of research:</h3>
<p align="justify">
First of all, I will look into the overall level of economic development of the country. On the one hand, there are many factors which can affect the economic growth of the country - if a country is developed or developing, the natural resources, demographic situation, etc. So as the first step we will look into GDP growth per capita in different democratic groups, to look at any difference between them at all.
<ol>
  <li><b>The mean GDP per capita is different across different democracy groups</b></li>
As the second step, we will look into the strength and direction of the correlation between democracy and other factors, such as distribution of resources, political stability, state ownership. These factors are connected to the political and economic components of the economic growth of the country.
  <li><b>The level of democracy, equal distribution of resources, political stability, and state ownership of the economy correlate with economic growth of the country.</b></li>
Democracy directly affects different indicators that can boost the development of the country, so in the third step we will look into the whole picture to evaluate what indicator affects it most.
  <li><b>What factors, connected with democracy, affect economic growth the most?</b></li>
</ol>
</p>
<h3>Data Description</h3>
<p align="justify">For research, we will use the dataset of the World Bank Data and V-Dem observations. The World Bank collects information for decision-making in cooperation with UN, OECD, IMF and the national banks of the countries. Quality of data about particular country may depend on the state financial institution wiliness and ability to collect reliable data. V- Dem is international organization, which develop and collect measures about state of democracy in 174 countries since 1975. </p>

<h3> Main variables:</h3>
<ol>
  <li><b>Democracy</b></li>
 Question: How can the political regime overall be classified considering the competitiveness of access to power
(polyarchy) as well as liberal principles?
<br>Responses: 0: Closed autocracy; 1: Electoral autocracy; 2: Electoral democracy; 3: Liberal democracy.
<br>Years: 1900-2021
<br>Scale: ordinal
  <li><b>Equal distribution of resources index</b></li>
Question: How equal is the distribution of resources?
<br>Responses: 0 is for total inequality. 1 for total equality.
<br>Scale: continuous.
<br>Years: 1900-2021
  <li><b>Political stability</b></li>
Measures perceptions of the likelihood that the government in power will be destabilized or overthrown by possibly
unconstitutional and/or violent means, including domestic violence and terrorism.
<br>Scale: ordinal
<br>Years: 1996-2020
  <li><b>State ownership of economy</b></li>
Question: Does the state own or directly control important sectors of the economy?
<br>Responses: 0 – totally, 4 – very little
<br>Scale: Ordinal, converted to interval by the measurement model.
<br>Years: 1789-2021
<li><b>GDP per capita (annual %)</b></li>
GDP per capita is gross domestic product divided by population.
<br>Scale: continuous,
<br>Year: 1996 - 2021
</ol>
<h3>Methodology</h3>
<p align="justify">As we are oriented to do research with the most data, we will choose three years between 1996 and 2022 to analyze, as ‘political stability’ and GDP per capita are only available for this period. All the hypothesis will be tested for each of three years, then the difference or similarity of results will be discussed. </p>

<h4>Hypothesis 1. GDP per capita across different democracy groups is the same. </h4>
<p align="justify">
To test this hypothesis, we need to compare the GDP per capita between four groups of countries. We can do that by parametric or non-parametric methods, the usage of particular method depend on the data. ANOVA can be used when two conditions met: 1. Dependent variable interval; 2. The volume of compared samples (groups) of at least 30 objects or a dependent variable must have a normal distribution. If both conditions met, we will use ANOVA method, in other case Kruskal-Wallis.
<br>H0: the mean GDP per capita of the groups are the same.
</p>

<h4>Hypothesis 2. The level of democracy, equal distribution of resources, political stability, state ownership of
economy correlates with economic growth of the country.</h4>
<p align="justify">
Part of the variables are continuous, while others have ordinal scale. It makes the Spearman correlation most suitable method to test correlation between these variables.
<br>H0: there is no monotonic relationship between the democracy and the GDP per capita in the population.
<br>H0: there is no monotonic relationship between the equal distribution of resources and the GDP per capita in the
population.
<br>H0: there is no monotonic relationship between the political stability and the GDP per capita in the population.
<br>H0: there is no monotonic relationship between the state ownership and the GDP per capita in the population.
</p>

<h4> Hypothesis 3. What factors, connected with democracy, affect economic growth the most? </h4>
<p align="justify">To answer this question, we need to use the regression: type of the regression depends on the type of dependent
variable. In our case Y is continuous variable, so regression have to be linear. We have four independent variables -
democracy, equal distribution of resources, political stability, state ownership of economy.
<br>H0: beta coefficient is equal to zero
</p>

<h3>Sources</h3>
<p align="justify">
<br>1. Apolte, T. Democracy and prosperity in two decades of transition. Economics of Transition and Institutional Change 2011, 19, pp. 693–722.
<br>2. Alesina, Alberto, Sule Ozler, Nouriel Roubini, and Paul Swagel. 1996. “Political Instability and Economic Growth. Journal of Economic Growth 1(2): 189–211.
<br>3. Przeworski, A.; Alvarez, M. E.; Cheibub, J. A.; Limongi, F. Democracy and development: Political institutions and well-being in the world, 1950-1990, 1st ed.; Cambridge University Press: New York, United States, 2000, p. 303.
<br>4. Egorov, G.; Sonin K. Dictators and their viziers: Endogenizing the loyalty–competence trade-off. Journal of the European Economic Association 2011, 9, pp. 903–930
<br>5. Coppedge, Michael, John Gerring, Carl Henrik Knutsen, Staffan I. Lindberg, Jan Teorell, David Altman, Michael Bernhard, Agnes Cornell, M. Steven Fish, Lisa Gastaldi, Haakon Gjerløw, Adam Glynn, Sandra Grahn, Allen Hicken, Katrin Kinzelbach, Kyle L. Marquardt, Kelly McMann, Valeriya Mechkova, Pamela Paxton, Daniel Pemstein, Johannes von Römer, Brigitte Seim, Rachel Sigman, Svend-Erik Skaaning, Jeffrey Staton, Eitan Tzelgov, Luca Uberti, Yi-ting Wang, Tore Wig, and Daniel Ziblatt. 2022. "V-Dem Codebook v12" Varieties of Democracy (V-Dem) Project.
<br>6. Sen, A. Democracy: The Only Way Out of Poverty. New Perspectives Quarterly 2000, 17, pp. 28–30.
<br>7. Lührmann, A., Tannenberg, M. & Lindberg, S. I. (2018), ‘Regimes of the World (RoW): Opening New Avenues for the Comparative Study of Political Regimes’, Politics and Governance 6(1), 1–18.
<br>8. R. & Lindberg, S. I. (2015), ‘The Index of Egalitarian Democracy and its Components: V-Dem’s Conceptualization and Measurement’, V-Dem Working Paper Series 2015(22).
<br>9. Kaufmann, D. & Kraay, A. (2016), ‘Worldwide Governance Indicators’.
<br>10. Pemstein, D., Marquardt, K. L., Tzelgov, E., Wang, Y., Medzihorsky, J., Krusell, J., Miri, F. & von Römer, J. (2022), ‘The V-Dem Measurement Model: Latent Variable Analysis for Cross-National and Cross-Temporal ExpertCoded Data’, V-Dem Working Paper Series 2022(21).
<br>11. The World Bank. 2022. World Development Indicators. Washington, D.C.: The World Bank (producer and distributor).
</p>
