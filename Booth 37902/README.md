## 37902-50: Foundations of Advanced Quantitative Marketing

### Python code to implement each of the models discussed in the class

#### PS1: Logit Model

1) Estimate the parameters of the simple logit model 
2) Compute standard errors for your estimates

#### PS2: Nested Logit Model

1) Nested logit model

   (i) brands 1 and 4 in one next and 3 and 2 in another
   
   (ii) 1 and 2 in one nest and 3 and 4 in another
   
   * How many “rho” parameters will you need in (i) and (ii)?  
   * What do both these alternative models suggest in terms of the IIA restriction?
   
2) Compute the cross-elasticity matrix

#### PS3: Heterogeneity Model

1) Compute the nested logit elasticities 

2) Try out the IIA tests

3) Work on the observable heterogeneity model – both a priori and with interactions 

4) Latent-segment / latent-class / discrete heterogeneity model with 2 segments


#### PS4: Heterogeneity Model with Segments

1) Complete the discrete segment case 

2) Try 2, 3, 4, and 5 segments; BIC criterion

3) Compute the elasticities and show how IIA is now violated at the aggregate

4) Compute the posterior assignment and compare the size of the a priori segment sizes to the numbers allocated to the segments.

5) Try the concomitant variable model.


#### PS5a: Random Coefficients Model

1) Estimate the continuous RC model. Try different numbers of draws as well as antithetic draws. 

2) Try computing the elasticities and posterior parameter estimates for each household.

3) K means cluster based on these estimates and compare with assignments from the discrete heterogeneity case.


#### PS5b: Factor Attributes Model

With the OJ data try to estimate the factor map under the continuous case.


#### PS6: BLP Model for aggregate data


#### PS7: Control Function

Control function approach (Petrin & Train, JMR) to account for endogeneity with aggregate data

Household Data: margarine dataset


#### PS8: Bayesian Learning

* With PhysicDiff data (in Stata):

1) Bayesian learning model (physician detailing datasets)

Data: ED category (no learning for Viagra, only for Levitra and Cialis)

2) Allow for some unobserved heterogeneity across physicians with RC model – either the LC model or the RC model works here.

* With ED Category data:

3) Account for risk aversion

Are physicians more risk averse for Cialis than they are for Levitra? (Note that this requires you to allow gamma to vary across the 2 drugs – not typical but this is just an exercise)

4) Accommodate forgetting in the model 

### Dataset:

PS1~4: Yogurt100N
PS5: OJ300, Yogurt100N
PS6~7: CoffeeData
PS8: PhyDiff, ED
