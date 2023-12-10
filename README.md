# Business problem and project objective.

Maverik needs an accurate daily forecast of sales KPIs for a new store's first year of sales. Achieving this allows for more effective financial planning and accurate ROI documents. This project will be a success if it is able to yield a better forecast than the current model. Stakeholders will measure success with error rate (MAPE) and RMSE. This is a supervised regression problem where the predictors involve both categorical and numerical variables, and the target are four sales metrics. 

We created a rolling window forecast ```Prophet``` model that produces daily predictions for a given horizon period (365 days). This model takes into account new sales data, and re-trains the model to produce a more accurate prediction every day. Using this rolling forecast prophet model Maverik can predict the store sales for a new store and be able to create an effective and accurate financial plan and ROI documents.

In this project all the members of our team met on a regular basis to collaborate and come up with action plans to try out different time series models and succesfully complete the project within the provided timelines. Each of us tried different types of time series models and chose the best model that was able to generate the lowest RMSE which is the Prophet model. I contributed in each and every part of this project by being present to each and every team meeing on the planned time, being prepared and coming with up ideas and questions or concerns for each meeting, writing codes or details for some parts of each assignments. The runtime it took to train and test models were one of the major problem we encountered during this project. Some of the time series model like ARIMA, ETS and XGBoost were creating flat predictions for some of the sales metrics but produced great predictions for other sales metrics which was quite confusing. We had to think out of box by looking into how we can add seasonality ourselves into the model and tried different types of seasonality like weekly, monthly, yearly etc. This is the first time I ever tried modeling a time series model so I learned a lot about the different types of time series models, important parameters that needs to be tuned for the models and what they mean or represent. I also learned that we have to think about what factors affect the target variable that we are looking to predict and make sure they are present or represented in some way in the dataset for the model to provide the best possible predictions.

[Github Repo:](https://github.com/bvasherchan/ProphetTimeSeriesModel)

Below are the materials from this project.

1. [Business Problem Statement](Maverick_ Business Problem Statement.docx)
2. [Modeling Notebook](https://github.com/bvasherchan/ProphetTimeSeriesModel/blob/main/ProphetModel.ipynb)
3. [Presentation slides](Maverik Revenue Forecast Slides.pdf)

