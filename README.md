# Delhi Metro Network Analysis

![Banner](https://sundayguardianlive.com/wp-content/uploads/2023/03/WhatsApp-Image-2023-03-26-at-12.33.47-PM.jpeg)  

This project aims to analyze the Delhi Metro network using Python. By examining the structure, efficiency, and effectiveness of the metro system, we can gain insights into routes, stations, traffic, connectivity, and other operational aspects.

## Objective
The goal of this analysis is to understand how well the Delhi Metro handles passenger traffic and supports efficient commuting in the city. Specifically, we want to optimize routes, reduce congestion, improve passenger flow, and identify patterns in travel behavior.

## Analysis Process
To conduct this analysis, we followed the steps below:

1. **Goal Setting**: Determining what to achieve, such as optimizing routes, reducing congestion, or analyzing travel patterns.
2. **Data Collection**: Gathering data on metro lines, stations, connections, and transit schedules.
3. **Data Cleaning**: Cleaning the dataset to handle inconsistencies, missing values, and errors.
4. **Visualization**: Creating visual representations of the metro network, including route maps, passenger flow charts, and congestion heatmaps.
5. **Analysis**: Assessing how effectively the metro network meets operational targets and handles passenger traffic.

## Dataset
For this analysis, we use a dataset containing information on all metro lines in Delhi and their connections. You can download the dataset from the link below:

[Download Dataset](https://github.com/heyamay/Delhi-Metro-Network-Analysis/blob/main/Delhi-Metro-Network.csv)

## Getting Started
To run this analysis, you will need to set up your Python environment. Follow the instructions below to get started:

### Prerequisites
- Python 3.x
- Jupyter Notebook 
- Required Python libraries: `pandas`, `plotly`, `networkx`, `matplotlib`, `folium`

### Installation
You can install the required libraries using pip:

```bash
pip install pandas plotly networkx matplotlib folium
```

# Few glimpses of EDA:
### 1. Geospatial Analysis:
![Delhi Metro Network](https://github.com/heyamay/Delhi-Metro-Network-Analysis/blob/main/Delhi%20Metro%20Network.jpg)
In this section, we visualize the geographical distribution of Delhi Metro stations on a map. Using the latitude and longitude data of each station, we create an interactive map with markers representing each station. 

Each marker on the map shows:
- The station's name
- The metro line it belongs to

This visualization helps analyze the density of stations and how they are geographically spread across Delhi, giving insights into station distribution and potential areas for infrastructure expansion.

### 2. Number of Stations Opened:
![Number of Stations Opened](https://github.com/heyamay/Delhi-Metro-Network-Analysis/blob/main/No.OfMetroStationsOpened.png)

In this section, we examine the growth of the Delhi Metro network over time by analyzing how many stations were opened each year. By extracting the year from the station opening dates, we visualize the pace of network expansion and observe key development phases.

The bar chart below illustrates the number of stations opened per year:
- Some years show a rapid expansion, with a significant number of new stations opening.
- In contrast, other years have fewer or no new stations, possibly due to factors like planning, construction delays, or financial constraints.

This analysis provides a clear understanding of the temporal development of the metro network, highlighting periods of rapid growth and slower expansion.

### 3. Metro Line Analysis:
![Metro Line Analysis](https://github.com/heyamay/Delhi-Metro-Network-Analysis/blob/main/Metro%20Line%20Analysis.png)
This section presents a detailed analysis of the various Delhi Metro lines, focusing on two key metrics:
- **Number of Stations per Line**: The total number of stations on each metro line.
- **Average Distance Between Stations**: The average distance between consecutive stations for each line.

To better visualize these metrics, we have created two plots:
- A bar plot showing the number of stations for each metro line.
- A bar plot comparing the average distance between stations for each line.

### 4. Distribution of Delhi Metro Station Layouts:
![Distribution of Delhi Metro Station Layouts](https://github.com/heyamay/Delhi-Metro-Network-Analysis/blob/main/Distribution%20Of%20Delhi%20Metro%20Station.png)
In this section, we analyze the distribution of station layouts across the Delhi Metro network. The layouts include:
- **Elevated Stations**: Stations built above ground level.
- **Underground Stations**: Stations constructed below the surface.
- **At-Grade Stations**: Stations situated at ground level.

We calculated the frequency of each layout type and visualized these distributions in a bar chart. This analysis helps identify trends in station design across the network.

### Key Observations:
- **Elevated Stations**: Most stations in the network are elevated, a common choice in urban environments to save space and minimize land acquisition challenges.
- **Underground Stations**: There are fewer underground stations, typically found in densely populated or central areas where above-ground construction is less practical.
- **At-Grade Stations**: At-grade stations are the least common, possibly due to space constraints and traffic considerations.

This layout distribution provides insight into the engineering and planning decisions made for the Delhi Metro network.

# Summary
So, this is how you can perform Delhi Metro Network Analysis using Python. Metro Network Analysis involves examining the network of metro systems to understand their structure, efficiency, and effectiveness. It typically includes analyzing routes, stations, traffic, connectivity, and other operational aspects.

### 🚀 About Me
#### Hi, I'm Amay Jaiswal! 👋
I am a Data Analytics Enthusiast and  Data science practitioner

[Linkedin](https://www.linkedin.com/in/heyamay/)

