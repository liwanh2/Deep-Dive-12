# UK House Prices — Predictive Modeling

**Data:** UK Land Registry Price Paid Data – [https://landregistry.data.gov.uk/app/ppd](https://landregistry.data.gov.uk/app/ppd)

## Team

- Perry Huang — [liwanh2@illinois.edu](mailto:liwanh2@illinois.edu)  
- Yiqiu Song — [yiqius3@illinois.edu](mailto:yiqius3@illinois.edu)

## Statement Problem

House prices are a key indicator of economic activity and household wealth.    
We aim to examine how London housing prices change over time, including whether past prices influence future prices and how nearby areas may affect one another.  

## Research Question:

Does the rise in price of one UK property affect the other?    
We will use a Recurrent Neural Network (RNN) to analyze spatio-temporal dependencies.  

Data Source  
HMLand Registry Open Data \- UK Gov Data (via Bulk download)

## Features

- Price paid (**target variable**)  
- Building name  
- Street  
- Town or city  
- District / County  
- Postcode  
- Property type (detached, semi-detached, terraced, flat/maisonette, other)  
- New build? (yes/no)  
- Estate type (freehold/leasehold)  
- Transaction category (standard/additional)  
- Date (transfer date)

Methodology

1. Data Extraction  
- Download from the Land Registry(CSV)  
- Clean and preprocess data(convert datetime into pandas timestamps, and convert the dataset into pickle) 


2. Data exploitation and feature engineering   

3. Modeling  

4. Feature Importance  

5. Evaluation  
- Download from the Land Registry(CSV)  
- Clean and preprocessing data(handle missing data, convert datetime into pandas timestamps, and convert the dataset into pickle) 

## License

MIT License — see [LICENSE](http://./LICENSE).  
