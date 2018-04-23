# Understanding-and-predicting-Property-Maintenance-fees
## Dataset Information
This is based on a data challenge from the Michigan Data Science Team ([MDST](http://midas.umich.edu/mdst/)).
The Michigan Data Science Team ([MDST](http://midas.umich.edu/mdst/)) and the Michigan Student Symposium for Interdisciplinary Statistical Sciences ([MSSISS](https://sites.lsa.umich.edu/mssiss/)) have partnered with the City of Detroit to help solve one of the most pressing problems facing Detroit - blight. [Blight violations](http://www.detroitmi.gov/How-Do-I/Report/Blight-Complaint-FAQs) are issued by the city to individuals who allow their properties to remain in a deteriorated condition. 

## Data Analysis
Every year, the city of Detroit issues millions of dollars in fines to residents and every year, many of these fines remain unpaid. Enforcing unpaid blight fines is a costly and tedious process, so the city wants to know: how can we increase blight ticket compliance?
The first step in answering this question is understanding when and why a resident might fail to comply with a blight ticket. This is where predictive modeling comes in. All data has been provided to us through the [Detroit Open Data Portal](https://data.detroitmi.gov).

Data was cleaned and divided into two datasets, train.csv and test.csv from the below datasets:
* [Building Permits](https://data.detroitmi.gov/Property-Parcels/Building-Permits/xw2a-a7tf)
* [Trades Permits](https://data.detroitmi.gov/Property-Parcels/Trades-Permits/635b-dsgv)
* [Improve Detroit: Submitted Issues](https://data.detroitmi.gov/Government/Improve-Detroit-Submitted-Issues/fwz3-w3yn)
* [DPD: Citizen Complaints](https://data.detroitmi.gov/Public-Safety/DPD-Citizen-Complaints-2016/kahe-efs3)
* [Parcel Map](https://data.detroitmi.gov/Property-Parcels/Parcel-Map/fxkw-udwf)

Predicted the resident’s compliance with blight tickets in Detroit City. 
Performed data extraction, cleansing, feature engineering and implemented Gradient Boosting Classification algorithm. Achieved ROC area under curve score of 0.78.

Download train and test csv files from [here](https://drive.google.com/file/d/1baAFljc4ZaMpDA6TPAD6jrsw2nzZRaR7/view?usp=sharing)
