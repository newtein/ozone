# Ground-level Ozone Pollution

We employed this novel and pragmatic peel analysis model on US EPA’s Air Quality Dataset of ground-level ozone. After employing multiple data-science approaches (ARMA-ARIMA, HMM) and filters (Moving Average, Savitzky-Golay), we analyzed aftermath of the region (rural or urban) and week (weekends or weekdays) on ground-level ozone pollution and variation in its precursors.

# Summary

 This analysis of ground-level ozone formation is categorized into two categories first, Analysis of short-term fluctuations in its concentration and second, Analysis of long-term fluctuations in its concentration. Short-term fluctuations in ground-level ozone formation is dependent over chemical reactions with its precursors (NO2 and VOCs). Their regional and weekly variations are analyzed with the aid of correlation coefficient, a popular tool in the study of ozone formation.Studies show that VOCs play a key role in ozone formation in urban areas while ozone formation in rural areas is influenced by both VOCs and NOx. This inference is derived majorly due to two factors, first, no or less correlation between O3 and NO2 concentration (wave) in the urban areas; and second, high traffic in the urban areas that make ozone formation and degradation process more complex. These inferences that are obtained by wave analysis disregards the burgeoning presence and key role of NO2 in Ozone formation while peel analysis shows a significant correlation between O3 - NO2 concentration regardless of urban or rural counties. Unlike wave analysis, Peel analysis can be used to obtain an unified and region independent ozone formation results. 


<center> <b> NO2 + O2 - > O3 + NO </b>  </center>

<image src="https://raw.githubusercontent.com/newtein/ozone/master/images/cali_2016.jpg">


Weekend effect is a popular phenomenon in ozone formation. It is observed during higher ozone concentration on weekends than on weekdays despite of lesser traffic on weekends that in turn accounts for lesser precursor emissions on weekends. This effect plays a crucial role in ozone emission control strategies and developing automobile emission standards. This weekend effect is not clearly inferred by the correlation between O3-NO2 correlation (wave). It is observed that correlation between wave remains constant throughout the week that fails to depict any weekend effect while peel or high-frequency component is highly susceptible to changes in the environment. A significant positive correlation between O3 and NO2 concentration (peel) is observed during the weekends. Peel can be employed to further analyze and control ozone formation during weekdays and weekends along with its variation with NO2.

Long-term fluctuations in concentration of ground-level ozone is analyzed in California. A high correlation in ozone concentration (wave) is observed among various cities of California. Ozone formation is majorly caused by motor vehicle exhausts and Ozone formation is decreasing in California over the time. The decrement in pollution in a short time span can be only achieved by dedicated human efforts. Unlike other states of US, California has its autonomy to makes its own laws on automotive emissions. The urbanized infrastructure of California has burgeoning motor vehicles around 2.3 per household. This scalibily increases the scope for implementation of stringent motor emission laws and its effect can be observed with significant decrease in ozone concentration. California spends more than many countries to regulate motor vehicle exhausts with far more strict standards than US or EU. California implemented many program like LEV, ZEV to reduce motor vehicle exhaust. The reason for high correlation among cities is imposition of unified and stringent emission standards throughout California. In this analysis peel tends to depicts short distance associations only.  Additionally, it is evident from our analysis as the pollution of ground-level ozone decreased due to extensive human interventions correlation among cities increased. 


# Publication
Details of work will be available after Publication
