# Restaurant Chain - Demand Forecasting
* Problem description:
* Predict the number of orders for the upcoming weeks of the test data of a very big meal delivery company.
* Goal is to do demand forecasting  for upcoming weeks so that the centres will plan the stock of raw materials accordingly. 
* Task is to predict the demand for the next 10 weeks. weeks (146 - 155)

* Model:
* Historical data is used to build a xbm and lbm (gradient boost models) which can predict the orders for test data.
* An ensemble model is finally selected since it is giving the highest accuracy.
* Jupyter notebook and python3 is used for building the model.

* Files Description:
* train.csv, test_QoiMO9B.csv, meal_info.csv, fulfilment_center_info.csv - data files.
* final_prediction_ensemble.csv - final submission file.
* sample_submission.csv - sample file.
* genpact_datathon_model.ipynb - model file ipnb.

* How to reproduce the project:
* Download all the files into a folder.
* Install all the required libraries before running the file.
* Run the ipnb file provided cell by cell.

* Planned future release:
* Testing for other ensemble models: code will be updated.
* Testing for other forecasting techniques: code will be updated.
