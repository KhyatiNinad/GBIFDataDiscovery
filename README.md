
## GBIF Data Discovery##

**Robust Data Enrichment Process** for GBIF mediated data using **Software based Analytics Framework**. 

GBIF is an open-data research infrastructure which provides free and open online access to species occurrence (primary biodiversity) data through their Website & APIs. However, GBIF mediated occurrence data has certain limitations and gaps, due to various reasons like sampling biasness, lack of efforts or lack of coverage of distribution of organisms, etc.

Through data gap analysis, Data users can determine if available data is suitable and sufficient to address their research investigations. Data holders & Publishers can prioritize mobilization and digitization efforts. And so, we feel that there is a need for a flexible Data Analytics Framework which can be an integral part of the Data Enrichment Process. This framework should analyse any GBIF data set without any restrictions to geography, taxonomy and temporal boundaries.

Generally, we feel that data sets are very lengthy, bulky and tedious to obtain the right information. This brings in the idea to get a software driven data analytics in use and get right visualizations for all the data sets in an interactive framework which can help get insights through algorithms and analytics tools, all in the same platform. And so, we present GBIF Data Discovery to help Data Users and Data Publishers get insights in an effective manner.

The proposed Process includes the Analytics & Data Gap Visualization Framework - **GBIF Data Discovery**, to analyse all sorts of data gaps, for any region, for any period and at every taxonomic hierarchy level. 

The framework consist of built-in _Data Import scripts_, _Intelligent Algorithms_ to calculate _Ignorance Score_ and _Inventory Completeness_ and has _Rich Visualizations_ to analyse trends and gaps through _Interactive Dashboards_ and _Associative Filtering_ of Data. It can also be easily extended to incorporate other complex algorithms to analyse gaps, create new dashboards with in-built dimensions & features as well as make changes to data-import level logic, even by data users/publishers themselves.

To obtain GBIF Occurrence Data:

1. Export GBIF Data in Tab Separated Files either through download API or through query explorer from GBIF website
2. Place 1 or more occurrence.txt files in Folder E:\GBIF\occurrence (Path is configurable in the app)


To Install the Application:

1. Please install Free Data Visualization Tool - Qlik Sense Desktop from [QlikSense WebSite](http://www.qlik.com/try-or-buy/download-qlik-sense) after registration 
2. Copy the file "GBIF Data Discovery.qvf" to the QlikSense Home directory, typically, C:\Users\<youruser>\Documents\Qlik\Sense\Apps\
3. Open Qlik Sense Desktop. Go to Desktop Hub. 'GBIF Data Discovery' will be available. Click on it. 
4. Open the Data Load Editor and click on ‘Load Data’. The App will automatically generate all the Dashboards.
5. Open the ‘App Overview’ and View the Trends, using flexible filters and visualize the available data through interactive charts and maps
6. Obtain insights on Data Gap Analysis, either through the in-built KPIs or through self discovery
