README
================
Yiqian Xin, Laiang Yao, Charlotte Yuan
4/12/2022

# Executive Summary

## Dataset and Research Question (Charlotte)

We obtained our dataset from the Health and Aging in Africa: A
longitudinal Study of an INDEPTH Community (HAALSI) in South Africa. The
baseline survey, conducted by the Harvard Center for Population and
Development Studies, in partnership with the MRCWits Rural Public Health
and Health Transitions Research Unit aimed to study the drivers and
consequences of HIV and other NCDs in the aging population in South
Africa.

Adults aged ≥ 40 living in the Agincourt sub-district of Mpumalanga
province, South Africa were enrolled in the HAALSI cohort. Based on
predetermined inclusion criteria, this study ultimately surveyed 5059
randomly selected men and women (n = 2345, 46.3% men; n = 2714, 53.7%
women). Household interviews were completed between November 2014 and
November 2015 and collected data on the demographics, health, and
economic conditions of all individual participants.

A cross-sectional analysis using the baseline data from the HAALSI
survey was conducted to investigate the impact of alcohol consumption on
sexual risk behaviors among 5,059 older adults (40 years and above) in
South Africa. We identified two research questions as follows: 1) the
effect of alcohol consumption frequency on the chances of not using
condoms during risky sexual behaviors, and 2) the association between
the frequency of alcohol consumption and the number of sexual partners
in one’s lifetime. We hypothesized that the frequency of alcohol
consumption may be linked to an increase in high-risk sexual behavior
and the number of sexual partners in one’s lifetime in this population.

## Methodology (Yiqian)

In the HAALSI dataset, we selected relevant variables that fit our
interest, including primary exposure and outcome variables as well as
potential sociodemographic confounders (sex, age, marital status, etc.).
The exposure variable is the frequency of alcohol consumption, including
never, 1-3 days/month, 1-4 days/week, 5-6 days/week, and daily. The
outcome variables include condom use in risky situations of sexual
behavior and the number of lifetime sexual partners. Here, we defined
the risky situations as when drunk or buzzed on alcohol or high on any
other drug. Condom use was measured as a binary variable with Yes or No
as values. The number of lifetime sexual partners is an integral
continuous variable. Sociodemographic variables of observations include
sex (male and female), age (> 40 years old, integral continuous
variable), marital status (single and married), country (South Africa
and Mozambique/other), and highest education levels including no formal
education, Some primary (1-7 years), Some secondary (8-11 years),
Secondary or more (12+ years). All of the variables with levels above
were transferred into factor category and their levels were recoded for
our specific research questions.

First of all, we wanted to know the distribution of values of our
primary exposure and outcome variables. We used bar plots in polar
coordinates to see the distribution of two categorial main variables
alcohol consumption frequency and condom use. We used a histogram to see
the distribution of the number of lifetime sexual partners in males and
females, respectively.

To understand the relationship between the frequency of alcohol
consumption and condom use in risky situations of sexual behaviors, we
used a stacked bar plot because these two are both categorical
variables. After having a general eye-ball test of the relationship, we
wanted to know if there was any statistical association between these
two variables so we conducted logistic regression in the whole
population and stratified the results into female, male, younger age
groups (40–65 years old), and older age group (> 65 years old)
respectively. To see clearly the results of regression models, we chose
to present odds ratios (ORs) and 95% confidence intervals (CIs) in an
integrated forest plot with dots of ORs and with lines of 95% CIs.

To explore the relationship between the frequency of alcohol consumption
and lifetime sexual partner number, we chose to use the combination of
box plot, jitter plot, and violin plot because these plots can show the
relationship between one continuous variable and one categorical
variable and give information in different aspects. Box plot tells us
quartiles, maximum and minimum, and skewness of the number of sexual
partners in different alcohol consumption frequency groups. Jitter plot
helps the visual of the distribution of many individual data points. The
Violin plot adds the information on the density on top of the box plot.
Similarly, we also want to know the statistical association between
these two variables. In this context, we used linear regression models
both in the whole population and in the stratified age and sex groups. A
Forest plot is used to visualize the coefficients of different levels of
alcohol consumption frequency and their 95% CIs.

## Findings & Results (Leon)

From our preliminary descriptive visualizations, we conclude that the
majority of the population in our study never drink alcohol (48%). The
proportion of the other frequency levels is approximately the same,
ranging from 6% to 14%. When assessing the proportion of individuals
having unprotected sex during risky situations as well as with
HIV-positive sexual partners, both showed that the majority of
individuals used condoms in the situations mentioned above, with 85% and
98% respectively. It is evident that the number of sexual partners for
both females and males shows similar trends, which is highly
right-skewed, indicating that the majority of individuals have few
sexual partners and there are some outliers that might have over 25
sexual partners. Additionally, the males tend to have more sexual
partners than the females by comparison from the histogram.

From our visualization of the association between condom use and
different frequency levels of alcohol consumption, we could observe a
gradual increase in the proportion of individuals who do not use condoms
during risky sexual behaviors as the frequency of alcohol consumption
increases. However, the highest proportion of individuals who do not use
condom falls in the 1-4 days per week category. We believe that there
are some potential confounding variables that affect the causal
association between condom use and frequency of alcohol consumption. In
the stratified visualization, we used the odds ratio to assess the
association between condom use and alcohol consumption frequency levels.
For males, there was a gradual increase from once per month to 5-6 days
per week, followed by a small decrease for the daily category. For
females, there was a sharp increase from once per month to 1-4 days per
week and then a sharp decline to 5-6 days per week and the daily
category. With stratification of age, the highest for the younger (\<65
years) lies in the 1-4 days per week and the highest odds ratio for the
older group (>65 years) lies in the 5-6 days per week.

For the visualization of the lifetime number of sexual partners and
different frequency levels of alcohol consumption, we used a boxplot to
assess the median and IQR of each category instead of the mean due to
the fact that the distribution of the number of sexual partners is
highly right-skewed. The distribution gradually shifts to the right with
the increasing frequency level of alcohol consumption. Similarly, we
used linear regression for the assessment of the stratification of
potential effect modifiers. It is surprising to note that both females
and males have the highest coefficient with the less than once per month
category. There might some other potential confounder that affects the
association. Additionally, the coefficient increases more in the male
group. For the different age groups, the younger category shows a
gradual, stable increase while there seems to be no obvious pattern for
the older group.

Overall, we could observe a positive association of the number of sexual
partners/condom use in risky sexual behaviors with the different
frequency levels of alcohol consumption. However, due to the large
dataset and missing data, there could be potential confounders to
determine the causal relationship.
