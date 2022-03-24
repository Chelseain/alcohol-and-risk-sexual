# What has been done
1. Added `sex` into the dataset, wrote out a csv document, and updataed the folder `proposal` and `data`. (xyq, 2022-3-24)
2. Recoded `alc_consumption` and `alc_freq` into `alc`, and ploted figure 1-3 in the folder `plotting`. (YY, 2022-03-24)

# Final
## 1. Descriptive analysis of alcohol consumption
Recode `alc_consumption` and `alc_freq` into one variable.  
*Qestion*: what kind of graph should we make? Histogram / Bar plot seems too simple.
## 2. Descriptive analysis of condom use (2 variables)
Use `sex_risk` and `sex_hiv`.  
**Intended graph**: side-by-side bar plot.  
*Question*: Intended graph seems too simple.
## 3. Descriptive analysis of sexual partners (2 variables)
Use `sex_partners` and `sex_partners_24`.  
**Intended graph**: histogram.
## 4. Relationships between alcohol consumption and condom use
Exposure: One recoded variable.  
Outcomes: `sex_risk` and `sex_hiv`.  
**Intended graph**: side-by-side bar plot / line graph.  
*Question*: How to present models?
## 5. Relationships between alcohol consumption and sexual partners
Exposure: One recoded variable.  
Outcomes: `sex_partners` and `sex_partners_24`.  
**Intended graph**: line graph.  
*Question*: How to present models?
## 6. Stratified anaysis of relationship 1
Stratified variables: `age`, `sex`, `marital_status`, `country`, `c_bd_educ4`.  
## 7. Stratified anaysis of relationship 2
Stratified variables: `age`, `sex`, `marital_status`, `country`, `c_bd_educ4`.  
