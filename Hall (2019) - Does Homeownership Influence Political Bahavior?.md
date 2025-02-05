#### Title: Does Homeownership Influcence Political Behavior?
#### Author: Andrew B. Hall, Jesse Yoder
#### Link: https://www.andrewbenjaminhall.com/homeowner.pdf

#### 0. Introduction
The research stems from the inquiry on whether the formation of political beliefs and the decision on participating in the election come from personal economic circumstances. Hall thought this from the context of property ownership. 

#### 1. Elements of Framework
#### Theory
**Targets of Model**: 
**Similarities of Model to the Target**: N/A
**Model**: N/A
**Implication**: N/A

#### Empirical/Elements of Research Design (ERD)
**Targets of Research Design**: voter turnout/participation difference between voter with and without homeownership
#### Empirical Strategy
**Estimand**: Overall effect of buying a home along with any correlated changes that individuals make when they become homeowners that also affects political participation
**Data**: Administrative data on more than 18 million voters in Ohio and North Carolina with deed-level data on property ownership.
**Statistical Procedure**: Four versions (Orders follow from Tables)
- Difference-in-difference design with individual/year fixed effects (\gammma_i, \delta) for full sample
- Difference-in-difference design with home-value-by-year fiexed effect for only homeowners
- Difference-in-difference design with individual/year fixed effects (\gammma_i, \delta) for only homeowners
- (Stronger) DID design: synthetic matching approach where exactly matching individuals based on their turnout in four pre-treatment electoral cycles

#### Measurement Validity
**Interpretation**: 
- The merged data (Adiministrative voter files fo Ohio and North Carolina + Information on Property Ownership collected county-by-county) meaninfully represents the effect of homeownership on increment in participant rate

**Argument**:
- These variables are direct measure of the features of interest, with the care for three key issues.
    1. Mismatch for voter and a homeownership attenuates: datasets are high quality, only use information on name, street number, and street name to link records (less false positive); 96% of entries in the Ohio voter file are unique (less duplicate); Appendix A.1
    2. Don't observe individuals in Ohio purged prior to 2017: Non-homeowners are likely to be purged -> slightly overestimate turnout for non-homeowners -> underestimate the turnout boost from homeownership (Section 3.5)
    3. "Deadwood," data on move into/out of states Ohio home-owners/sellers: Overestimate the effect of homeonwershp in both cases; move-in voter whom they had been long time voter and move-out voter who continues voting, since impute their turnout as zero after they move
    -> To account to 2/3, adjustments were made (written in Confidence Building) 

#### Substantive Identification
**Assumption**:
1.  Parallel Trend (PT): changes in individuals' turnout behavior after purchasing a home at time *t* would be the same as changes in turnout behavior for individuals who did not purchase a home at time *t*.
    - Deduct concerns that the individuals chose to purchase homes in times when they become wealthier
2. Individual *does not* select into homeownership for many time varying, unobservable reason
3. The decision of homeownership does not stem from those point their life when they are making other changes
4. Selection observables: the rate of purge between homeowners and non-owners are equal

**Arguments**: Critically evaluate the validity of these assumptions.
- (PT) Add leads of the homeowner variable, to see evidence of pre-trending; found substantively very small coefficient on these leads, and the coefficient on the main effect for homeowner remains similar in magnitude
- (PT) Redo results using country-by-year fixed effects; homeowner's counterfactual trends are computed using only individuals who did not buy a home but live in a same county
- (PT) Estimate a version of DID that makes comparisons only among the set of people who purchase a home at some point; everyone in this sample archieves the wealth necessary to be a homeowner
- (PT) Include a separate set of time fixed effects within each decile of the home purchase prices; counterfactual trends are computed among people with similar levels of wealth but who purchased their homes at different times (Columns 2 and 3 in Table 1)
2. Exactly match individuals on the basis of their turnout over four electoral cycles; find a control group likely to offer more accurate counterfactual trends
    - dataset is large and outcome variable is binary
3. Use variation in the size of the effect to get at the underlying mechanism of the effect; direct link between being homeowner and acting to protect one's financial interest in one's home
    - changes in adult roles; bias our estimates upward if such leads individuals to be more likely to buy a home and become more invested in politics
    -> provide suggestive empirical evidence;
    1. estimate the effect separately for each year of birth; 25 yr old > 55 yr old by 4 percentage point --> the estimate can be a function of changing roles in early adulthood 
    2. rely on infromation info about the type of properties (i.e. Single Family Residence); sort out a potential individual with the intention of planning for children
    -> evidence suggest that dult roles and other life events could explain some, but not all of the effect of becoming a homeowner

#### Confidence Building
To combat the overestimation on the effect of homeownership where the paper impute turnout equal to zero for those whose age made them eligible to vote but did not turn out (e.g. just moved in/out to/from different states), done robustness check
- Adjustment 1: drop individuals whose registeration year >= year of their home purchase (potential moved in)
- Adjustment 2: set turnout to missing for individuals after they sell their home (pontential moved out)
- Result were larger than the original result in Table 1; out-of-state mover is very small fraction of the dataset

#### 2. Commensurability


#### 3. Reinterpretation
#### Provide alternative interpretations of the findings.

#### 4. Elaborating
#### Expand on how the literature review contributes to future research.
- Multiplying Measures: four different DID designs to bolster Substantive Identification, mainly assumption of Parellel Trend

#### References
#### List all references in a consistent and proper citation style.

#### Memo
- Found that (theory focuses on local policy) becoming a homeowner increases the propensity to participate in national elections.
-> homeownership causes a more general shift in individuals' attention
- Is the "cemetries" vote lower salience for additional effect of homeownershiop on turnout? Suppose the government decides to build a new cemetries, it might affect their property value
- The paper suggests links between homeownership and national elections; extends homevoter literature that suggests homeowners should be relatively indifferent to national politics