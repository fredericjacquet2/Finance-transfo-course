## Chapter 3 - Digitalising Performance management : leveraging the Business Partner Finance

1. Digitalisation of FP&A / Reporting & Performance management: data analysis and datavisulisation 
2. Going beyond digitalising existing processes, and moving towards predictive performance management with Machine learning over Big Data & Analytics

----

#### Chapter 3.1 Digitalisation of FP&A / Reporting & Performance management 

- Data extraction & analytics to provide ad-hoc reporting, with data taylored to various users needs
- Datavisualisation = customed extraction & presentation, tailored to user needs    

*Specific solutions based on BI (Business Intelligence) and EPM Enterprise Performance Management softwares* 

----

<img src="images/bi2.jpg" style="background:none; border:none; box-shadow:none;"/>

----

> Case example IPSEN « FIT Finance Ipsen Transformation » (source Digital Finance Awards 2019)

- Digital dashboards = reporting tool, real-time, anywhere (PC/mobile/tablet), fit-for-purpose (adapts to each user), interactive & fancy (graphs & drill down) to check sales, costs, P&L on a given perimeter.
- Result : lower solicitation of cost control on support presentations, better appropriation of the financial data by operations.

----

### Technology : BI, OLAP cube, Dataviz and EPM

- Business intelligence (BI)  = applications, infrastructure and best practices that enable access to and analysis of information to improve and optimize decisions and performance.      
- BI process = collecting, organizing, and analyzing data, and turning it into useful and actionable information.     
- BI end-user functionalities : drill-down / roll-up, ad-hoc reports, interactive dashboards, mobile reports ...     

----

Data management (from raw data to fancy reporting)      
<img src="images/OLAP3.jpg" style="background:none; border:none; box-shadow:none;"/>      

----

-	First challenge : centralising the data in a single Warehose (ETL products)     
-	Second challenge : have a quick & efficient access to required information (the OLAP cube)     
-	Third challenge : presenting the information in a clear, nice and tailored manner to the user (data visualisation functionalities)     
-	And a last challenge (for next chapter) : finding patterns in the warehouse’s data, in order to predict trends.  

----

The OLAP cube (Online Analytical Processing) : 

-	Pre-compute all the totals and subtotals needed for reporting
-	Totals are stored in a special database called « OLAP cube » which is a snapshot of data at a specific point of time.
-	OLAP cube efficiency : instant access to data (no need to loop through any transaction, as all totals are precalculated)
[5 min on OLAP & Relational DB](https://www.youtube.com/watch?v=2ryG3Jy6eIY)

----

<img src="images/olap3.png" style="background:none; border:none; box-shadow:none;"/>      

More details on Bi implementation [here](https://www.altexsoft.com/blog/business/complete-guide-to-business-intelligence-and-analytics-strategy-steps-processes-and-tools/)

----

BI products : [Tableau](https://www.tableau.com/fr-fr), [Power BI](https://powerbi.microsoft.com/fr-fr/), [IBM Cognos]([Looker](https://looker.com/), [Chartio](https://chartio.com/), [Domo](https://www.domo.com/), [Qlik](https://www.qlik.com/us/), [IcCube](https://www.iccube.com/) ...        

OLAP tools : IBM Cognos, MS SQLServer Analysis Services SSAS,          

FP&A / EPM (Enterprise Performance Management) products: Anaplan,       

----


#### Chapter 3.2 : Leveraging the Business Partner Finance with Big Datza & Analytics (from cost control towards performance management in predictive mode)

- A finance function closer to the business ("business partner finance") 
- A finance function closer to technology (IT/ BI / EPM... )
- A finance function Master of the Data
- Predictive rather than reactive

----

> QUOTE by Accenture (" Finance 2020 ")  

"Finance is doing things that it never could before thanks to digital technologies. The finance organization will evolve from an expense control, spreadsheet-driven accounting and reporting center, into a predictive analytics powerhouse that creates business value. Tomorrow’s digital finance organization deals in analytics and forward-looking decisions to create value and manage risk. It shifts traditional accounting and processing to cross-functional integrated business services models that use robotic process automation. It trades reporting the past for predicting the future."

----

WIP (Work In Progress) 

> QUOTE by xxxxxxxxxxx 

"Finance ...."

----

<img src="images/dassault.png" style="background:none; border:none; box-shadow:none;"/>

----

A two-fold approach for the Business Partner Finance : 
1. Abality to generate taylored made, real-time reporting : BI / EPM tools 
2. Capacity to leverage the "usual" performance management reporting towards predictive performance management : Big Data (Data lake, Data factory) and Analytics (IA, Machine learning) 

----

> **Case example BARILLA (source Digital Finance Awards 2019 & other sources)**     

- Promotional offers optimization : solution called TPO (Trade Promotion Optimization)
- TPO is dedicated to sales & forecasters teams, with responsibility assigned to Finance
- allowed to consolidate Business Partnering
- Development of IA Machine learning models, Big Data & Data analytics
- Result : forecast promotion ROI on innumerous variables (multiple products, dozens of segments, specific stores, time of year).

----

### Technology : Big Data & analytics / IA (wip)

----

<img src="images/BIGData.png" style="background:none; border:none; box-shadow:none;"/>      

----

> APPENDIX / Illustration : Online sports betting actor     

- Market : very competitive + strong growth
- Objectives : increase market share and profitability of the sport betting activity
- Specific focus : Customer acquisition cost 
- Initial information : net cost of promotional offers, market share evolution, BU profitability

----

Key questions: 
- What is the impact of the promotional offer on increasing market share? 
- What is the ROI of the promotional offers ?

To provide some answers:
- Understand and differentiate player behaviours and player types according to presnet & future context

----

The project:
- Setting up a project-oriented organization, lead CFO + CDO
- Set-up a Data factory (Data lake)
- set-up analysis algorithms from:
  - Historical data from structured databases (several years of history)
  - Internet player end behaviour recording
  - Unstructured, real time data (social networks, news…) analysis implementation
- Main key analysis: player profile / sport type / timeline

----

Result: 
- Predictive analysis
- Optimization of customer acquisition cost, depending on the context (type of game, games to come)
- Improved sports BU profitability

----

* end of chapter 3 * 
