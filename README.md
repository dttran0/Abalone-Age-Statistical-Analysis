## Introduction:
Abalone are large marine gastropod mollusks that are sought after for their shells and their meat, and were once considered a food staple for many indigenous culturesaround the world. While abundant in 
numbers during the 20th century, decades of overfishing, climate change and disease have decimated wild abalone populations,and they are at risk of extinction. According to an article titled "All West Coast Abalone
at Risk of Extinction on the IUCN Red List" posted to the UC Davis website by Kat Kerlin, as of 2022, all 7 of the US abalone species that live on the West Coast have been listed as either Critically Endangered or Endangered 
by the International Union for Conservation of Nature. In California alone, warming ocean temperatures and mass decline of kelp forests have dramatically affected wild abalone populations. It is important for us to play a role 
in abalone conservation efforts, and save them from extinction before they are lost from the world forever.

## Dataset Description
The Abalone dataset: Collected from 1994 from Tasmania Coast, where the abalone species is indicate as Haliotis species
Contained 9 prediction features. Obtained the actual age (in years) by adding 1.5 to the rings parameter


## Research Question
What are the significant features or set of features in predicting and analyzing the Age (in years) of abalone?

To examine this question more closely, we decided to construct the posterior simulation for single features fit and also extend to multiple features fit


## Prior
Examined the mean age of Haliotis species type, in which typical age of abalone ranges from 10 years olds, and able to live up to at most 30-40 years old. We will
denote our prior understanding with N(10, 5)


## Conclusion
Based on our analysis from the regression models, credible intervals, MAE summary, and ELPD estimations, we have found that height is the most significant predictor
affecting our response age, with diameter, length, viscera weight, and shell weight as the next most significant.
The model comparisons inform us that model 7 demonstrates the highest posterior predictive accuracy without applying every single predictor

## Limitations
With more times and resources, we can extend on these refinement We would run every single possible model (we didn't have the time to do this, already
takes 2 hours to run ours) Dataset is dated from 1994, so we would collect data from abalone in 2024


## Future Direction
Our Bayesian models might help researchers and marine biologists understand the relationship between abalone age and its other physical measurements, and better
develop their knowledge of abalone. Our results can aid in the future establishment and operations of abalone conservation efforts, and also development of breeding
programs
