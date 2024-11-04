### Notes on _Family History Matters: Immigration Stories Moderate Policy Opinions_

In this replication project, 
the authors aimed to examine how different family immigration histories influence one’s sentiment towards open immigration policies and empathy towards immigrants. 
Based on data from an experimental survey, they further investigated the varying effects of specific reasons related to one’s family immigration history. 
They studied both the effect of knowing one’s family history and the priming effect of one’s family immigration history. 
They claimed to have found that economic motivations behind one’s own family’s immigration to the U.S. lead to less favorable attitudes toward open immigration policies, 
while closer proximity to the immigrant generation within one’s own family fosters a more positive attitude towards open immigration policies and empathy for immigrants.

First, the replication script functions well. 
I was able to smoothly replicate the results with the data and script provided by the authors. 
Second, the draft is well-written, with clear interpretations of the results.

The following points are worth noting:

1. **To what extent is the conclusion about the effect of different family immigration histories on one’s policy attitudes and empathy valid?**
   Although the coefficients for economic reasons are significant in both figures,
   it may be questionable to conclude that citizens whose family immigration history involves economic factors are more likely to oppose open immigration policies.
   This is because the data used comes from an experimental survey, which does not guarantee representativeness.
   Such a conclusion can be reliably drawn about the respondents in the study, but it may not be directly applicable to the broader population.

   The original study is experimental and, therefore, does not require a representative sample,
   as its purpose is to establish a causal relationship between the variables.
   However, if the goal is simply to describe the relationship between two variables,
   a representative sample would be necessary. Otherwise, the conclusions would only be valid within the specific sample used.

   Personally, I believe there are likely to be varying effects due to different reasons for immigration among the population,
   and I also believe it is very likely that the directions of effects you found are consistent with those in the broader population.

   However, with a non-representative sample, the validity of your findings is limited.

3. Based on the previous point, I wonder **if you would consider focusing on the priming effect of economic and humanitarian motivations**,
   as both are significant in your tables.
   Since your data comes from an experimental survey,
   it is legitimate for you to discuss the priming effect, and you have strong evidence supporting the existence of such effects.
   These effects vary between different groups.

4. Assuming that the issues mentioned above are not a concern, I would suggest paying attention to the model specification.
   Currently, you are using a linear model, which may raise some doubts, although I do not think it is a major issue.
   In your model, the dependent variable could potentially take unrealistic values, such as 0 or 8 for policy attitudes, and -1 or 101 for empathy,
   although in fact they cannot.
   If you were to use an ordered logistic regression model, this issue or possible doubt would not arise.

