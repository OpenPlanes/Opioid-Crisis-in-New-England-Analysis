# Opioid-Crisis-in-New-England-Analysis
Opioid Crisis in New England Analysis


With a great acceleration of deaths by fentanyl overdose during the CoVid-19 pandemic, the United States are battling against synthetic opioids being smuggled inside the country and its dramatic consequences. By trying to understand the dynamics driving the fentanyl epidemic in the United States using a compartmental model, precious insights could be provided to policymakers to counter the social and economic effects illicit drugs have on the country as a whole.

Ofﬁcial data show that fentanyl-related overdose deaths have spiked after 2012. According to our model, the main parameters impacting this concerning increase are the extremely high prescription opioids addiction rates, the loose recovery rate and, of course, the deadliness of fentanyl (being 50 times more potent than heroin). Tailor-made policies should account for the sensitivity of the fentanyl epidemic system to these factors, trying not to focus on a prohibitionist approach. In fact, drug seizures and bans should be applied with care: a restrictive policy might even increase the number of fentanyl deaths by overdose in the long run.

1. 1999 - 2012 Compiled and Cleaned Data
   <img width="713" alt="figure_2" src="https://github.com/OpenPlanes/Opioid-Crisis-in-New-England-Analysis/assets/106100235/0567f552-29f7-400b-a219-94824c4f048e">

   This data, representing the number of deaths attributed to each of the three substances over 100,000 individuals
   As it can be seen from the figure, heroin deaths started to increase since the early 2010s. Despite growing earlier than fentanyl overdose deaths, the latter grew with a steep exponential tendency starting from 2013. In fact, deaths caused by fentanyl overdose increased by about 450% over the period 2014-2019. While in 2016 fentanyl continued to increase, heroin started to marginally decrease. Finally, for the whole 20-years period in consideration, prescription opioid deaths were stable, averaging over 3.5 deaths for each 100,000 individuals in the US.

2. First Model
   <img width="889" alt="first model" src="https://github.com/OpenPlanes/Opioid-Crisis-in-New-England-Analysis/assets/106100235/46f713d5-a0d2-4c5e-b7de-c0a32cc2b8d5">

   In particular, given the estimated conversion rate ω and the average number of people belonging to each compartment, an average of 5.46 individuals transitioned yearly from heroin to fentanyl in a voluntary way. This speciﬁc transition is not the biggest channel bringing people to the Fentanyl compartment: the proportion of people entering F is dominated by individuals that buy heroin laced with fentanyl without them being aware of it, especially when the laced rate φ gets closer to 50%.

3. Sensitivity Analysis - Prescription Relationship
   <img width="705" alt="relationship with prescription" src="https://github.com/OpenPlanes/Opioid-Crisis-in-New-England-Analysis/assets/106100235/38650b16-09d9-486e-a269-2f7d67f91096">

   As it can be seen from Figure 6, S has a decreasing trend. Its variance increase until the last year. Compartment H has an increasing behaviour until the 15th year in consideration, and then decreases. F has an increasing behaviour and a relevant variance, particularly towards the end of the analysis. R has an increasing trend with a variance that always rising when the year increase.

4. Policy Analysis
   <img width="702" alt="policy relationship" src="https://github.com/OpenPlanes/Opioid-Crisis-in-New-England-Analysis/assets/106100235/c71c4e5f-c231-458d-9a52-cf3de3ac2367">

   The prescription opioids market could be regulated in a better way. Prescription opioids are the gateway drug for opioid addiction, as about 80% of people addicted to illegal opioids ﬁrst misused prescription  A conclusion is that limiting the supply of prescription opioids would end one of the main path of opioid addiction, leading to a future scenario similar to the one that can be seen  where we simulated our model with a α parameter reduced by 50% of its initial value. A possible drawback of this intervention is that it could push prescription opioid users (taking pills for either medical or recreational reasons) towards heroin use. An hypothetical limitation to the supply of prescription opioids could increase (and not decrease) the addiction rate (in our model, α): the ban could backﬁre and cause an increase in addiction to illegal drugs in the short-term, while scenarios are hard to predict in the long-term. This projection, involving an increase in prescription opioid addiction, is showed in  In this case, fentanyl would reach an endemic equilibrium.

Curing the opioid epidemic is hard and by any means we are not handing the solution in the next paragraph, but throughout our research we noticed several things that could be improved, starting from collecting more data. The only way to improve something is to measure and understand it ﬁrst, and this is not done with the vast majority of recovery programs in the United Sates. It is very hard to ﬁnd statistics about the success rate of these programs and, in the few cases in which the data is actually collected, very few people’s progress is traced after they end the program. We believe that an improvement in the data collection process and effort in tracking recovered users after they ﬁnish the program, even years later, could bring very valuable insights on the epidemic. The last projected scenario plotted in  clearly shows this qualitative reasoning: increasing the recovery rate ρ by 100% would drastically reduce fentanyland heroin-related deaths in the year to come.
