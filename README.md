<h1> Analyzing Transjakarta Operational and Travel Duration Performance </h1>

## 1. Project Overview
This project analyzes business data to extract insights, improve decision-making, and identify key trends. The primary focus is to **understand operational performance for Transjakarta and  analyze factors affecting Transjakarta travel duration**

Key Objectives:
- Analyze operational performance of Transjakarta (route, bus stops, and peak hours)
- Identify factors affecting travel duration
- Analyze travel duration performance across different service/routes and time periods

## 2. Data Source
- Transjakarta - Public Transportation Transaction (kaggle.com/datasets/dikisahkan/transjakarta-transportation-transaction) -  Simulated Data for Card Transaction in Transjakarta


## 3. Technologies Used
- Programming Language: Python (e.g., Pandas, NumPy)
- Visualization: Matplotlib, Seaborn
- Interactive Dashboard: Tableau
- Version Control: Git
- Others: Jupyter Notebook

## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
|
├── data
│   ├── raw            <- Data from third party sources.
│   └── cleaned        <- The data that has been cleaned.
│
├── notebooks          <- Jupyter notebooks.
│
├── reports            <- Generated analysis as PowerPoint, PDF, LaTeX, etc.
|   ├── slide          <- Generated PowerPoint
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Finding
### 5.1 Business Insight
**Operational Condition Analysis**
- The number of passengers and the number of routes are mostly found in BRT/Non BRT and Mikrotrans services
- The average number of passengers per route for each service is relatively the same
- The routes with the largest number of passengers are Ciputat - CSW, Harmoni - JIS, and Pulo Gadung - Monas
- The stations with the largest number of passengers are Penjaringan, Garuda Taman Mini, and BKN
- Transjakarta rush hour occurs at certain times, namely in the morning (05.00-09.00 WIB) and afternoon (16.00-21.00 WIB).

**Travel Duration Analysis**
- The services with the longest travel duration are Rumah Susun, Royaltrans, and Wisata, with a time range of 34-40 minutes.
- There is no correlation between the number of passengers and travel duration
- Initial fluctuations in travel duration start at 07.00 to 09.00. Then during the day, fluctuations occur at 12:00 - 13:00. Then the next fluctuation occurs at 15:00, and the duration of the trip remains relatively high until 21:00. 
- In addition to the Tour service, there is no significant difference in the duration of the trip each day for each service.

### 5.2 Actionable Recommendation
1. Prioritize service improvements on the Ciputat - CSW, Harmoni - JIS, and Pulo Gadung - Monas routes
2. Prioritize service and infrastructure improvements at the Penjaringan, Garuda Taman Mini, and BKN bus stops
3. Take advantage of commercial, retail, and advertising opportunities at the Penjaringan, Garuda Taman Mini, and BKN bus stops
4. Increase the frequency of public transportation during peak hours, namely in the morning (05.00-09.00 WIB) and especially in the afternoon (16.00-21.00 WIB) to reduce passenger waiting time
5. Re-evaluate routes with long average travel durations.
6. Add routes with dedicated lanes for Transjakarta buses to avoid getting stuck in traffic jams.

## 6. Contact
- Name: Kevianwillie Handoyo
- Email: kevianwillie.h@gmail.com
- Linkedin: https://www.linkedin.com/in/kevianwillie-h-92247b137/