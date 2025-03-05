# Development of a Machine Learning-Based Load Shedding System for Optimized Energy Manangement with University of Lagos as a Case Study

## 1.1 Background of Study  
Nigeria's electricity sector is characterized by a complex interplay of challenges that have resulted in a persistent energy crisis. These challenges include a significant deficit in generation capacity compared to national demand, aging and poorly maintained transmission and distribution infrastructure, and inefficient management practices. This has led to frequent power outages, load shedding, and an unreliable grid, significantly hindering economic growth, industrial development, and social well-being. The impact of these power sector challenges is felt across all sectors of the Nigerian economy, from manufacturing and agriculture to healthcare and education.  

Within the educational sector, consistent and reliable electricity is crucial for effective teaching, learning, and research. Universities, in particular, rely heavily on electricity to power classrooms, laboratories, libraries, administrative offices, and student accommodations. The University of Lagos, a prominent federal university in Nigeria, is no exception. Like many other Nigerian institutions, it experiences frequent disruptions to its power supply, directly impacting its core functions. These disruptions hinder academic activities, impede research progress, disrupt administrative operations, and negatively affect the overall campus experience for students, faculty, and staff. The reliance on generators as backup power sources further compounds the problem, leading to increased operational costs, noise pollution, and environmental concerns due to emissions. The need for a more sustainable and reliable energy management solution is therefore critical for the university to effectively fulfill its educational and research mission. The current reliance on load shedding as a means of managing the supply-demand imbalance, while necessary in the short term, highlights the urgent need for more intelligent and efficient approaches to energy management within the university setting.  

## 1.2 Problem Statement  
The University of Lagos faces significant challenges in managing its growing energy demands, especially during peak periods when electricity consumption surpasses the available supply. The university currently employs a rigid, time-based load shedding schedule. This system allocates power based on fixed time slots, supplying electricity to administrative and educational buildings between 8:00 AM and 6:00 PM, and to residential areas from 6:00 PM to 8:00 AM. This approach, while simple to implement, lacks the flexibility to adapt to real-time variations in energy demand.  

This inflexibility creates several problems. Firstly, critical facilities may experience power shortages during peak demand periods, while other areas consume unnecessary power when their demand is low. Furthermore, the system fails to accommodate fluctuating needs, such as increased power demand in lecture halls and laboratories during examination periods or reduced daytime demand in residential areas. The power outages in residential areas during the day disrupt students studying or working from their accommodations. As such, unused electricity allocated to certain facilities cannot be redirected to areas with higher demand, leading to wasted energy. Given these problems, a transition towards an intelligent data-driven system offers a promising solution.  

## 1.3 Aims and Objectives of the Study  
This project aims to develop a machine learning-based load shedding system for optimized energy management at the University of Lagos. The project will leverage a clustering-based approach to group buildings based on their estimated hourly energy consumption and subsequently build a predictive model to forecast future total campus energy use.  

The specific objectives of this research project are to:  
- Conduct a survey for estimating hourly power consumption for individual buildings and transformers.  
- Develop a machine learning-based clustering algorithm to group buildings based on estimated hourly energy consumption patterns.  
- Develop a machine learning-based load shedding system for optimized energy management at the University of Lagos.  

## 1.4 Significance of Study  
This study is significant because it addresses the critical challenge of inefficient energy management at the University of Lagos, particularly given the constraints of limited data availability. By developing a machine learning application that utilizes a clustering-first approach based on estimated building-level energy consumption, this project has the potential to:  

- **Provide insights into building energy usage patterns, even without direct metering:** By estimating consumption based on appliance inventories, the project offers a practical way to understand how different building types contribute to the overall campus load.  
- **Offer a practical solution despite data limitations:** The project addresses the lack of individual building metering by using a combination of estimation and available total campus load data, demonstrating a viable approach for other institutions facing similar data scarcity.  
- **Enable more informed load shedding decisions:** The application provides predictions of total campus energy consumption and dynamically adjusts load shedding strategies based on these predictions and the estimated building clusters, moving away from rigid time-based schedules.  
- **Improve energy efficiency at the campus level:** By optimizing load shedding based on predicted demand and estimated building contributions, the application aims to reduce overall energy consumption and lower operational costs for the university.  
- **Provide a foundation for future improvements:** The methodologies developed in this project, particularly the estimation approach, can serve as a valuable stepping stone towards more sophisticated energy management systems once individual building metering infrastructure becomes available. The insights gained from the appliance-based estimations can also inform future energy audits and efficiency initiatives.  

## 1.5 Scope and Limitations of the Study  
The scope of this study is limited to the development and evaluation of a machine learning application for intelligent load shedding at the University of Lagos, utilizing a clustering-first approach based on estimated building-level energy consumption. The project will focus on:  

- Developing a methodology for estimating hourly energy consumption based on appliance inventories and typical usage patterns within each building. This will involve conducting building surveys to identify and quantify the appliances present.  
- Developing and implementing a clustering algorithm to group buildings based on these estimated hourly energy consumption patterns.  
- Developing a predictive model for total campus hourly energy consumption using available historical data and relevant external factors.  
- Designing and implementing a dynamic load shedding strategy based on the identified building clusters and predicted total campus load.  

### Limitations  
The primary limitation of this study remains the absence of individual building-level energy consumption data from dedicated meters. While the project addresses this by estimating consumption based on appliance inventories, this estimation approach introduces several limitations:  

- **Accuracy of Estimation:** The accuracy of the estimated building-level loads depends on the accuracy of the appliance inventories and the assumptions made about their usage patterns. This estimation will inherently have a degree of uncertainty.  
- **Time-Consuming Data Collection (Appliance Inventory):** Conducting building surveys to create appliance inventories will be a time-consuming process. This limits the scale of the data that can be collected and the level of detail that can be captured.  
- **Reliance on Typical Usage Patterns:** The estimation methodology will rely on assumptions about typical appliance usage patterns, which may not perfectly reflect actual usage. Variations in individual behavior and building occupancy can affect actual energy consumption.  
- **Inability to Capture Real-Time Data at the Building Level:** Even with estimations, the application will not be able to capture real-time fluctuations in energy consumption at the building level. Load shedding decisions will still be based on predictions and estimated contributions to the total campus load.  
- **Impact on Clustering Accuracy:** The accuracy of the building clusters will be affected by the accuracy of the estimated building-level loads. This could lead to suboptimal load shedding strategies.  
