# cian-parser-example
That is the example of how data collected with https://github.com/farimano/cian-parser can be analyzed to build real estate evaluation model.
## The description of files
1) 00_scraping.ipynb and 01_scraping.ipynb are basically examples of how use cian-parser to scrap and parse data.  
2) 02_geo_features.ipynb and 02_geo_prices.jpg - geo features collecting and geo research.  
3) 03_add_house_info1.ipynb and 04_add_house_info2.ipynb - data mining with open data by gkh site https://www.reformagkh.ru/analytics (unfortunately, this site is available only in Russia). The main challenge of these two notebooks is the join by address and address approximation methods.  
4) 05_final_cleaning.ipynb is devoted to feature selection and the preprocessing of collected gkh information.  
5) 06_model.ipynb - catboost regressor learning  
6) 07_metrics.ipynb - the most interesting notebook with the evaluation of the model. The notebook contains classical regression metrics and other post analysis.