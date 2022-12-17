# Sri Lankan Inflation using Web Archives

The Sri Lankan economic crisis in 2022 caused many hurdles for Sri Lankans, which included the soaring prices of everyday items. 
The general increase in prices of goods and services, termed [inflation](https://www.investopedia.com/terms/i/inflation.asp), 
must be maintained at an optimum level for an economy to thrive. 
However, inflation beyond the optimum levels is harmful to an economy.  

The calculation of inflation is primarily done using a [Consumer Price Index (CPI)](https://www.investopedia.com/terms/c/consumerpriceindex.asp), 
which examines the prices of a basket of goods and services over a period of time. 
The basket's composition can vary based on the country or region to reflect the consumption habits of the population. 
Sri Lanka uses two CPIs, [National CPI (NCPI)](http://www.statistics.gov.lk/InflationAndPrices/StaticalInformation/MonthlyNCPI) for the entire country 
and [Colombo CPI (CCPI)](http://www.statistics.gov.lk/InflationAndPrices/StaticalInformation/MonthlyCCPI) for the capital population center. 
Even though the CPIs can capture the overall inflation in an economy, it does not provide information on inflation at the product level. 

In this study, we attempt to uncover product-level price changes with the archived web pages of an online retailer. 

## Dataset
The raw dataset comprises ~2800 archived pages of [Glomark](https://glomark.lk/), one of the major online retailers in Sri Lanka. 
The processed data in the repository include manually selected mementos that capture pricing details of the products (rice, dairy, and soap) 
considered in the study.

|File name| Description|
|---|---|
|`dairy.csv`| Details of mementos capturing prices of dairy products |
|`rice.csv` | Mementos containing prices of rice |
|`soap.csv` | Mementos capture price details of soaps |

Each `csv` file contains following columns.

| Column | Description| 
|---|---|
|`year,month,day` | Date of the memento |
|`url` | URL of memento (archived page) |
|`<product-name>` | Product price captured by memento. |

`<product-name>` `cheese,yoghurt,butter` for dairy, `samba,nadu` for rice, and `dettol` for soap.

-- Bhanuka Mahanama([@mahanama94](https://twitter.com/mahanama94))

