# Building Defect Repository

Task 1: is to do feasibility study to explore getting building defect data online using Web Scraping techniques. 
I used Python libraries such as Http requests, BeautifulSoups and Selenium. (https://github.com/wellia/WebScrapping)

Task 2: Cleaned, analysed and mined the data with Python, Spacy, NLTK (https://github.com/wellia/buildingDefect/blob/main/buildingDefect_process.py)
Visualized the data with tableau BuildingDefect_general, BuildingDefect_responseDays, BuildingDefect_elements dashboards (https://public.tableau.com/app/profile/wellia.lioeng#!/)

Task 3: build models to predict the building defect categories. 
- I performed data analysis. The result was inconsistent data entry and highly imbalanced data
- I cleaned the data, selected categories and performed data augmentation
- To train a model, I implemented ktrain (https://github.com/amaiya/ktrain#overview), a Lightweight Neural Network wrapper for Keras. The model is trained with DistilBERT, light and faster transformer model based on BERT. (https://paperswithcode.com/method/distillbert). The accuracy is 73%. (https://github.com/wellia/buildingDefect/blob/main/buildingDefect_process.py)
- Using this model, I predicted categories for new data
- I also experimented with machine learning xgboost, random forest (https://github.com/wellia/buildingDefect/blob/main/buildingDefect_model_ML.py)
