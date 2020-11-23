# Human-Freedom-Index-Project
_Variables from the original dataset:_  
**year** <dbl> - A year from 2008-2017  
**countries** <chr> - Country name  
**region** <chr> - Region name  
**hf_score** <chr> - Human Freedom score from 0-10  
**pf_score** <chr> - Personal Freedom score from 0-10  
**ef_score** <chr> - Economic Freedom score from 0-10  
**ef_government** <chr> - Government size score from 0-10 (10 = smaller government)  
**pf_religion** <chr> -  Freedom to practice a religion of one’s choosing 0-10 


_Variables created from the dataset:_  
**diff_ef_pf** <dbl> - Difference between economic freedom score and personal freedom score per observation  
**coldwar_side** <chr> - Described whether country was Soviet or Western during the Cold War (for relevant countries)  
**ws_score** <dbl> - Overall score for women's specific freedoms 
**hfi_women_unweighted** <dbl> - Human Freedom score from 0-10 with women's freedoms unweighted
**pf_score_nowomen** <dbl> - Personal Freedom score from 0-10 with women's freedoms unweighted  
**ef_score_nowomen** <dbl> - Economic Freedom score from 0-10 with women's freedoms unweighted  
**mean_pf_religion** <dbl> - Mean religious freedom score from 0-10 for each region 
**mean_ws** <dbl> - Mean womens-specific freedom score from 0-10 for each region
**religion_avg** <chr> - Represents whether a country's pf_religion score is above or below average
**ws_average** <chr> - Represents whether a country's ws_score score is above or below average
  
