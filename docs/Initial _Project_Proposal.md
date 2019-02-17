# Project McNulty Proposal

*Jhonsen Djajamuliadi*



**Title:**

- _**You are what you eat!**_  i.e., How does our food choices or physical activity affects our health?



**Scope**: 

- Obesity-related diseases are the leading causes of death in the United States [1]. People that are obese have higher chances of developing heart disease, hypertension, stroke, and even (some) cancers [2]. Although nobody seeks out ways to become obese, many would agree that they could (and should) live a better and healthier lifestyle. This irony brings into question whether our (seemingly harmless) habit of snacking or dining out affects our chances of becoming obese. Furthermore, one may wonder how the lack of physical exercise affect our weight and overall health.  

  

**Methodology**: 

- Collect the American Time Use Survey (ATUH) dataset and store it into local database with PostgreSQL 

- Obtain a subset of the dataset and analyze: 

  - Determine which survey questions to include and do exploratory analysis
  - Feature engineering some of the survey answers 

- Build a classification model to predict BMI category (i.e., Underweight, Normal, Overweight, or Obese)

- Create a dashboard with widgets, to illustrate a person's chance of becoming obese based on his/her choices of food, drink, and activity

    

**Data Sources**:  

- [Kaggle dataset](https://www.kaggle.com/bls/eating-health-module-dataset)
- [Bureau of Labor Statistics](https://www.bls.gov/tus/ehdatafiles.htm)



**Prediction** (**Target**):  

- **Body** - a person's BMI category, i.e., obese, overweight, normal, underweight [3].  



**Features**  

|  No  |  **Name**   |           **Description**           |
| :--: | :---------: | :---------------------------------: |
|  1   |   TimeEat   |    Time spent eating (minutes)?     |
|  2   |  TimeSnack  |   Time spent snacking (minutes)?    |
|  3   |    Soda     | Soda choices: diet, regular, both?  |
|  4   |    Drink    |     Beverages aside from water?     |
|  5   |  Exercise   |         Physical exercise?          |
|  6   | ExFrequency |       Frequency of exercise?        |
|  7   |   FFWeek    | Purchased any fast food this week?  |
|  8   |  FFW_freq   |  Frequency of fast-food purchase?   |
|  9   |    AdeqF    | Did they feel like they eat enough? |
|  10  |   FFYest    | Purchased any fast food yesterday?  |
|  ..  |     ...     |                 ...                 |
|  ..  |     ...     |                 ...                 |
|  30  |     ...     |                 ...                 |

 **References:**

1. *Leading causes of death* report from [CDC](https://www.cdc.gov/nchs/fastats/leading-causes-of-death.htm)
2. *Health risks of obesity* from [MedlinePlus](https://medlineplus.gov/ency/patientinstructions/000348.htm)
3. *Defining adult overweight and obesity* from [CDC]( https://www.cdc.gov/obesity/adult/defining.html)

