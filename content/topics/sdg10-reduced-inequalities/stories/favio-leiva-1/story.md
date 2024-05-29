---
title: On Ethnic Diversity and Development in Bolivia
author: Favio Leiva
date: 2024-05-29
data: "/data/GeoDS4Bolivia.geojson"
categories: ['Inequality','Diversity', 'HHI' ,'Sustainable Development Municipality Index']
---

Some authors argue that if there is more diversity, more creativity arises, and more output is generated (for an extensive discussion on the issue revise Alesina & La Ferrara (2005)). In this short article, it’s shown that there is a negative relation between the Herfindahl Hirschman Index (HHI hereafter) of Ethnicity at the Municipality level (Instituto Nacional de Estadística, 2012) in 2012 and the Sustainable Development Municipality Index (Andersen et al., 2020) in 2020 respectively. For a discussion on the HHI revise Herfindahl (1950) and Hirschman (1945). The formula is the following:

$$HHI_j = \sum_{i=1}^4 S_{ij}^2$$

Where $S_i^2$ is the squared share of ethnic group i in each municipality j multiplied by 100. If there is a higher value of that index, then we have more concentration (less diversity). If it’s lower, there is less concentration (more diversity). By construction, the possible outcomes are only 4: Indigenous, Non Indigenous, Non Bolivian and Unspecified. Therefore, ideally, the minimum theoretical value can be 2,500 and the maximum, 10,000. 
To make an interpretation of this index, we shall note that when it is closer to 10,000, it means that only one ethnic group concentrates all the population. When it is closer to 2,500, there is more diversity (each of the 4 groups have similar populations). If we make a disaggregation of more groups, the indicator could become closer to 0. In a scatter plot, a negative slope means that more diversity is correlated with a higher dependent variable.

![Figure 1. HHI in the base estimate vs Sustainable Development Municipality Index](stories/favio-leiva-1/HHIinthebaseestimatevsSustainableDevelopmentMunicipalityIndex.png)

In figure 1 we can see that there is a negative relation between the Sustainable Development Municipality Index and our measurement of ethnic diversity. This means that there is more development, in general, in those municipalities where there is more diversity. However, if we separate by indigenous majoritarian or non-indigenous majoritarian municipalities, we see that this only holds for the indigenous municipalities.

In figure 2 we see that the negative relation is clearer when using NTL per capita in 2012. This means that the results are sensitive to what dependent variables are used. Here, the results hold also for non-indigenous municipalities. The main message here is that there is more illumination and, therefore, GDP in more diverse municipalities. 

![Figure 2. HHI in the base estimate vs NTL per capita in 2012 (LN)](stories/favio-leiva-1/HHIinthebaseestimatevsNTLpercapita2012(LN).png)

But why does this happen? We shall explore in more detail the components of the Sustainable Development Municipality Index. Maybe there are some processes going on in the components of that index. It’s important to point out that other controls could be added in both cases which could reduce the dispersion and make more patent the negative correlation between the two dependent variables we used in this short article. That’s a task for future studies. The main message of this blog entry is to point out that there are huge chances ethnic diversity also promote development. Conflict also may arise and if that happens, institutions to promote mutual understanding and peaceful ways to solve differences shall be enhanced. There are still gaps to close in Bolivia. Policies to decolonize Bolivia and promote ethnic equality still have many challenges ahead. 

References
- Alesina, A., & La Ferrara, E. (2005). Ethnic Diversity and Economic Performance. Journal of Economic Literature, 43(3), 762–800. http://www.jstor.org/stable/4129475
- Andersen, L. E., Canelas, S., Gonzales, A., & Peñaranda, L. (2020). Atlas municipal de los Objetivos de Desarrollo Sostenible en Bolivia 2020. Universidad Privada Boliviana, SDSN Bolivia. www.sdsnbolivia.org/Atlas
- Herfindahl, O. C. (1950). Concentration in the Steel Industry.
- Hirschman, A. (1945). National Power and the Structure of Foreign Trade.
- Instituto Nacional de Estadística. (2012). Censo Nacional de Población y Vivienda 2012. https://redatam.org/cdr/descargas/censos/poblacion/CP2012BOL.zip
 


