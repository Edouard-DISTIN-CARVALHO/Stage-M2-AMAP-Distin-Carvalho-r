# Stage-M2-AMAP-Distin-Carvalho-r

**Relating patterns in woody stem respiration with bark plant functional traits**

CERFogo & NEOFIRE Projects – Estação Ecológica da Serra das Araras, Brazil. 

Supervision: Imma Oliveras Menor, Wesley Jonatar Alves da Cruz, Francisco Navarro-Rosales

## Questions : 

### 1) **What is the impact of fire on stem respiration of Cerrado trees over time?** 
H0 : In the long term, trees subjected to frequent fires would exhibit lower respiration rates.
H1 : In the long term, trees subjected to frequent fires would has no change in their respiration rates.

**Analyses:** 
• Genral Linear Mixed Models (GLMM) of the individual mensal rates stem respiration rates as a function of the fire regime values relate with the species as fixed factors, with the variability between trees was included as random factors since like (tree-tag, species). The air temperature are already include on the calculation of C02_efflux so we didn't incluede them on the model. 

**Data:** Compilation of monthly stem respiration data from 2018 to 2024, but we select to use the most recently data of the years of 2023. We don't select the year of 2024 because of the big drougt which happened this year but we will do the same analysis with this data to compare the two ones. 

### 2) **How do the  barks functional traits influence the stem respiration of Cerrado trees?** 
H0 : Trees with thicker bark would have lower respiration rates than trees with thinner bark.
H1 : Trees with thicker bark would not have changed their respiration rates compared to trees with thinner bark.

**Hypothesis:**  
We expect find relationship between some traits which can influence the CO₂ diffusion. For example, we expect a negative correlation between outer bark thickness and density (Loram
Lourenço et al., 2022). So, this relation between would most influence the CO₂ diffusion. 

**Analysis:** 
• Pearson correlation test between the mean values of bark functional traits across all trees in the plot no burned (ESA-04) to identify which traits are corelate between them 
(Loram-Lourenço et al., 2020 ; Rosell et al., 2014).   
• PCA: to explore the multivariate associations between all the other bark functional traits no correlate and put the estimate of stem respiration across all tree species in the plot 
no burned (ESA-04) (Loram-Lourenço et al., 2020 ; Rosell et al., 2014). 
• Linear Models (LM) of the estimate stem respiration rates as a function of the mean bark trait values as fixed factors. We will determine which bark traits explain most of the variability in stem respiration rates by comparing models using performance criteria (Ávila-Lovera & Winter, 2024). At the same time, we will realize trade-off comparison between the bark traits and relate them to the stem respiration.  

### 3) **What is the impact of the barks functional traits in Cerrado trees subjected to variations in fire regime?**
H0 : Trees with thicker bark that are exposed to more frequent fires would have lower respiration rates than trees with thinner bark that experience fewer fires.
H1 : There are no change of stem respiration between trees exposed to more frequent fire with thicker bark and trees exposed to fewer fires with thinner bark.

**Analyses:**  
• PCA: to explore the multivariate associations between all bark functional traits and stem respiration in each plots with different fire regimes to observe the associations 
difference between the plot (Loram-Lourenço et al., 2020 ; Rosell et al., 2014). 
• Linear Models (LM) of bark functional trait values as a function of tree species in interaction with fire regimes. We will determine which bark traits explain most of the variability in stem respiration rates by comparing models using performance criteria. At the same time, we will realize trade-off comparison between the bark traits and relate them to the stem respiration of each plot with different fire regime.  

**Data:** Continuous quantitative data of the mean bark functional traits and estimate of stem respiration per species and across all the experiment.  
Estimate of stem respiration of 2023 of all the plot linked with bark functional trait data from the March 2025 campaign. We will compare the value of stem respiration and 
bark traits between the plot with different fire regime.
