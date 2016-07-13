Municipal Services in India
===========================


Challenges
----------

India is rapidly urbanizing and it is seeing an increase not only in population but also living standards. These factors are resulting in increased demand for urban services such as safe and reliable water supply and prompt removal of waste water and solid waste. However, these services rely upon increasingly scarce natural resources - fresh water supply sources and water bodies and land to safely absorb and break down waste.

Because of the haphazard development and unplanned urbanization, Indian municipalities not only provide inadequate services but the services are grossly inquitable. Poor neighborhoods and slums either do not have municipal infrastructure servicing them or see large disruptions in service.
   
Municipalities do have well-intentioned folks doing their best with the resources at hand and deal with challenges such as political interference, poverty (and inability to pay for services), aging infrastructure, frequent discontinuties in leadership, lack of environmental and social education, etc.  
 
However, each municipality faces specific challenges which SmartTerra intends to help solve:

- Lack of operational visibility: There is very little data collected and most of the data is usually not digital. As an example, the GIS description of hundreds of KMs of water pipeline network is usually offline in small cities which means that field workers mostly dig first to search for pipes. 
- Ad-hoc resource management: Most municipalities have a large workforce but task management and task co-ordination is mostly offline and verbal. There also is a lack of automation, solicitation of feedback and very little knowledge transfer of best practices. 
- Reactive maintenance: 
- No support for innovation:

Municipalities services such as water supply, waste water removal, solid waste removal, etc are delivered to a geographically distributed population.


Smart Urban Platforms
---------------------

The goal of a smart city is to improve the quality of urban life by using technology to improve the efficiency of services, reduce costs, improve resource utilization and most importantly, meet residents’ needs. For urban India, where the resources are at a shortage amidst high demand, smart cities need to have another important objective - transparency and equitable distribution of services. These objectives implicitly mean improved environmental outcomes.

In order to improve the efficiency of their services, smart cities will need to organize their services into clearly defined processes and tasks. They will have to organize their assets and workforce while assigning well-defined responsibilities. The spread out geographical area should be organized into manageable chunks. The citizens to whom the services are being provided should be mapped to the municipalities assets, workforce and geographical entities providing the service. A municipal service being provided to a citizen and the citizen's feedback about the service should be easily tracked through the various resources and hierarchies of the municipality. 
  
The city cannot improve what it cannot measure. Hence, it needs to add visibility about the performance and costs to each of the service's providers, the service's processes and resources and the area the service is provided in. Visibility immediately improves service levels.

The data that the city collects should easily map to the various resources and hierarchies of the municipality. The data being collected can be from simple surveys and mobile apps used by the municipal staff or citizens or can be from complex and expensive but automated sensors and devices. The source of the data doesn't matter as much as the process being illuminated by the data. The data thus collected should be put to use in reducing costs and improving resource utilization by analyzing each of the municipal processes in the service delivery and helping in the operational and managerial decision making.

The data platform should enable the municipality to interact directly with the citizens and to explain the services transparently and obtain feedback. Most importantly the data platform should enable innovation, both from within the municipality as well as the wider community.


SmartTerra is developing an open source urban data platform for municipal services. The first service to be developed will be fresh water supply. The features of the platform are described below in the context of water supply.



India Smart Cities
------------------

The smart city documents for the [first phase of the smart city challenge](http://smartcities.gov.in/Cities_Profile.aspx) provide a lot of context.

In addition the PEARL initiative of the NIUA has published this document for [best practices in water supply and sanitation.](http://pearl.niua.org/sites/default/files/books/GP-IN2_WATSAN.pdf) 

In the following sections we will discuss some details of the water supply situation in Kakinada, Hyderabad and Nagpur. 


### Hyderabad

Coming soon!

### Kakinada

Lets take a look at how Kakinada, a city of about 3.5 lakhs in Andhra Pradesh, handles its water supply. This section gives an overview of the infrastructure, processes being followed and the scope for improvement.

Kakinada's main source of raw water is the Godavari Canal through summer storage tanks. The present water supply is 45 MLD with a per capita supply of 107LPCD. NRW was 35% in 2015 and is expected to be reduced to 20% in 2016 because of the network renewal as part of the APMDP scheme. 

Kakinada supplies water twice daily; between 6am-8am and 5pm-6.30pm. Kakinada treats 0% of its wastewater/sewage and all of it is let out into the Bay of Bengal. Since there are quite a few industrial and institutional customers and since there is reasonably decent surface supply, Kakinada makes an operational profit with water.

Kakinada's Smart City applications can be found at these links - [SCP](https://www.dropbox.com/s/a5i50ym7rhjxkaa/kakinadaSCP.pdf?dl=0) and [Annexure](https://www.dropbox.com/s/7r4pdr9vkxic0xz/KakinadaAnnexures.pdf?dl=0). 

**Existing Network**

Kakinada has approx. 60,000 households in 50 wards. The municipality has 1200 borewells and two summer/intermediate storage tanks at Aratlakatta (1582ML capacity) and Sambamurthy (821ML capacity) which are fed from the Godavari River via the Kakinada and Samalkota canals, an open-surface source. The raw water is treated at the Water Treatment Plant (WTP) at the municipality water works of which the primary settling tank is shown below. The WTP has two sets of Rapid Sand Filter beds. 

![Townhouse Settling Tank](./content/images/townhouse_settlingtank.jpg)

There are 9 pump stations with each containing 2-4 pumps each of 60-240HP capacity. There is a diesel generator available at each of the pump stations.

Water is pumped from the storage tanks into the WTP and then on to sumps and elevated storage reservoirs (ELSRs). There are 15 ELSRs which service the 50 wards.

There are 4 tankers of 10,000L capacity with the municipality and 6-8 private tankers which are outsourced by the municipality or are filled by the municipality. On a given summer day of May 5th 2016, there were 21 trips carrying a total of .11MLD made by the 4 municipal tankers, 58 trips carrying a total of .44MLD made by 6 private tankers. 

**Processes**

The municipality tracks the amount of water in the summer storage tanks on a daily basis. It tracks a key metric - sustainabilty. The Telangana government and the Andhra government track the cities' water situation in the publicly available[TS PHMED](http://www.tspublichealth.gov.in/dailyStatusReport.do) and  [AP PHMED](http://www.appublichealth.gov.in/dailyStatusReport.do) websites.  
These websites contain the details for sustainability periods, deficit reports, statuses of pipelines, borewells, etc.

The Kakinada municipality enters a daily summary into the [Urban Water Supply](http://uwsis.cgg.gov.in) website which is then aggregated over all the cities into the AP PHMED website mentioned above. 

Every day the level of water in the two SS tanks is manually monitored and entered into registers as well as the UWSIS website. The register is shown below. The sustainability calculations are then done by simply determining the amount of water remaining in the tank and the assumed constant demand.

![SS Tank Capacity](./content/images/SS_tank_level.jpg)

The filtering capacity of the filter beds is monitored at every hour of the day with remarks about the chlorination, backwash, etc.

![Filter Bed Monitoring](./content/images/WTP_filter_capacities.jpg)

The duty cycle (amount of ON time) for the pumps in various pump houses is also monitored. Downtime of pumps because of maintenance is also noted in the UWSIS website. Pumps are usually in pairs and do breakdown frequently because some of them have been installed in the 1970s. The register entries for the pump ON times  and the status of the ELSRs that they each service are shown below.

![Pump Duty Cycle](./content/images/pump_dutycycle.jpg)

Listed below are the ELSRs and their capacities (alongwith the number of samples taken for the Residual Chlorine test). 

![ELSRs Capacity and RC Samples](./content/images/ELSRs_quality.jpg)

In addition to the daily RC sampling at the ELSRs, daily sampling is undertaken at 270 places geographically distributed in the city. The geographical spread should ideally be completely random but depends a lot on the 10 or so linemen under the purview of the Tap Inspectors. In addition to the daily sampling of the RC, there is periodic quality testing of other parameters as well and these too are entered into a register shown below.

![Periodic Quality Testing](./content/images/Quality_Testing.jpg) 

**Smart City Plans**
**SmartTerra** 

### Nagpur

Coming soon!


Existing Water Platforms
-----------------------

The below are summaries for water analytics companies.

Company | Brief Description
------- | -----------------
IBM Intelligent Water | IBM® Intelligent Water software delivers smarter water management through insights from data to help utilities manage pressure, detect leaks, reduce water consumption, mitigate sewer overflow, and better manage their water infrastructure, assets and operations. This software uses advanced data management, visualization, correlation and collaboration technologies to transform the vast amounts of disparate data received from various devices (including metering systems), assets, systems and stakeholders into actionable information that can guide executive and operational decision-making. Intelligent Water is a water management platform that enhances infrastructure visibility to deliver an advanced level of situational awareness, event and incident management, informed decision-making and collaboration among stakeholders.
AmigoCloud            | AmigoCloud is a next-generation mapping technology company, providing mobile Geographic Information System (GIS) solutions with advanced offline support. Available on Android and iOS devices, AmigoCloud makes geospatial data collection, administration, and sharing simple.
Ayyeka                | Supplies water flow, quality, level, etc kits. Seems like primarily a hardware company. Ayyeka provides cyber-secure, plug-and-play, remote monitoring solutions designed for various markets
Apana                 | (was Kirkland Analytics)  Smart sensors placed in select areas of your facility scan the water infrastructure around the clock capturing high resolution data down to the second. These sensors send data to a secure, cloud-hosted analytics engine that continuously looks for patterns and discrepancies to isolate waste events across 1000’s of failure points. When waste is detected, mechanical failures and operational breakdowns are identified at the source. Staff is instantly notified with actionable guidance. Alerts contain automated step- by-step instructions telling operators that there is a problem, where it is, and how to resolve it. Managers get insights to improve processes.
Golagoon              | Lagoon sensors take the current meter infrastructure of the facility or commercial site and make it smart. The meters will be happy to join the Industrial Internet of Things. Lagoon's learning algorithms forecast your water usage, finds anomalies, such as leaks, and identifies inefficiencies, while providing insight and control over your water usage.
DropCountr            | Dropcountr connects people and their utilities on the mobile devices they use everyday. Our unique mobile and web applications help water utilities and their customers save water, save money and save time. In a world dominated by mobile apps, we connect utilities and consumers on mobile, as well as web and paper to help everyone conserve water. Utilities can deliver customized drought and water budget messages instantly. Users are notified of damaging leaks immediately.
TaKaDu                | TaKaDu is a leading software provider of Integrated Event Management solutions for the water sector, empowering utilities to manage their networks efficiently. Based on big data analytics, TaKaDu's IoT cloud-based solution enables water utilities to analyze and manage the full life-cycle of network events, such as leaks, bursts, water pressure issues, water quality and faulty assets. Using raw data from multiple sources, TaKaDu helps utilities detect problems (‘events’) early, reduce water loss, shorten repair cycles and improve customer service. The technology offers in-depth visibility and quick insights into every type of event, facilitating smarter decisions.
WaterSmart Software   | "We use utility meter data to better communicate with residential customers and help them save water, energy, and money. Water suppliers also receive analytics that reveal insights into customer consumption and program participation trends. 1. Program performance reporting 2. Customer segmentation and geospatial analytics 3. Customer Relationship Management (CRM) capabilities 4. Rebate program participation metrics 5. Leak and high use alerts 6. Manual read, AMR & AMI compatible 7. Reduced staff time"
Valor Water           | Valor’s mission is to transform utility data flows worldwide into actionable decision making through innovative technology. One solution in the suite is SMART Targets for Conservation. We build a data connector to your system and then display results through a secure web-based client-specific portal. Results are based on the latest water consumption behavior and updated on a daily, weekly, or monthly basis, depending on meter data read frequency and client needs. Client users can log in and interact with the functionality on the portal to generate reports for various client audiences, including executive reports, progress and evaluation reports for individual and aggregate residential and commercial customers, and reports summarizing outcomes, cost, and ROI for specific campaign conservation efforts.
PowWow                | Our suite of applications includes the Pump Monitor™, which provides automated water records by leveraging existing smart meters from power utilities. It protects farmers from the operational downsides of anomalies such as leaks or falling water tables. The Irrigation Advisor™ simplifies irrigation scheduling solution by integrating data from the cloud (weather data and aerial images) and from local farm records (nutrient application and on-site sensors). Growers receive simple text messages in the field, not more data at the office.
WatrHub               | By harnessing the power of data and software, we enable young, innovative water technology startups all the way up to $1B+ equipment manufacturers, make empowered decisions about where and when to sell & market their water & wastewater treatment solutions.
Wellntel              | With Wellntel's groundwater level sensing system you'll have groundwater information and trends at your fingertips: you can see what happening with your groundwater, if your well and your pump are running as they should, or if they need attention from an expert. You can see how levels in your well change seasonally or annually, which direction the water level is heading, and you can set alerts to be notified if the level is getting low or your pump or water system needs attention.
Cadisfly              | Indian water quality non-profit but importantly uses Akovo Flow which can be used by SmartTerra for the Android+GPS+Data
Fluid                 | Kickstarter+SF company measures water usage and leakage via ultrasonic. From the kickstarter seems like they do only copper pipe and that too 3/4inch.
Calliope              | Water metering for smart homes. https://www.youtube.com/watch?v=dlGfDFqlayA
Smarterhomes          | Bangalore based company with water meters. 
 



Smart Urban Water Platform
==========================

As can be seen from the examples of Kakinada, Hyderabad and Nagpur, cities need an open data platform which provides a destination database to organize the various data sets involved in a urban water supply and to then make intelligent decisions based on the data. SmartTerra is such a platform and in the below sections we describe the platform and its features.

The SmartTerra platform can be broken down into four chunks - CityView, CityData, CityApps and CityDevices. The platform is a combination of a features usually found in GIS platforms, ERP systems, IoT platforms and (big) data visualization and analytics. The platform is designed to work with SCADA systems, IOT devices, commonly used SQL databases, etc. 


CityView
--------

A municipality delivers services over a large geographical area. For e.g. water supply is a treatment, transmission and distribution of water from a (few) central location/s to numerous customer endpoints or connections. Customers, their meters/accounts and their feedback will be geographically spread out. The transmission/bulk and distribution networks will be geographically spread out 

Most municipalities in India have mapped their network into GIS databases using tools such AutoCad, ArcGIS and more recently Google Earth.  



CityData
--------  
A few ways to look at data.
- Excel
- DataHero: 


CityApps
--------


CityDevices
-----------


Team & Mission
==============

Coming soon!



