# UCLA ITS Data Camp 2019
Curriculum, coursework, and associated material for the Fall 2019 UCLA ITS Data Camp.

### Course Goal
Students should be able to walk away with the knowledge to complete a small analytical project of their from start to finish own using the tools introduced to them in the class.

### Major Topics
- Data Definitions, Project Organization (20%) 
    - The landscape of tools & resources
    - Intro to Notebooks (we will be using Jupyter notebooks), Code Commenting, Markdown 
    - Organizing Projects, Presenting Findings, Reproducibility  
- Getting & Wrangling Data (50%)
    - Using libraries (finding the right package, installing, importing into code)
    - Getting Data: From reading flat files such as CSVs, from the web using an API
    - Reshaping Data (Pandas)
    - Writing helper functions 
    - Writing Output
- Analytical Tasks (30%)  
    - Summarizing data to produce findings
    - Leveraging libraries to produce graphs & charts
    - End course with brief intro into types of models, Sci-Kit learn, etc.

### Prerequisites
- Knowledge:  Students should have some basic working programming knowledge already and should be able to write small functions, install & import relevant packages, and be able to perform some basic data manipulation.  Students who complete the Coursera course [Programming for Everybody (Getting Started with Python)](https://www.coursera.org/learn/python) will be prepared.  
- Software: Anaconda w/ Jupyter Notebook setup & installed. Tim will be available to help with any install issues before the class starts.

### Course Format
Morning: Work through notebook examples from Geoff Boeing's [Urban Data Science course](https://github.com/gboeing/urban-data-science) & any other lecture material  
Late Morning / Afternoon: Students complete exercises (unfinished notebooks) prepared by Tim  
Afternoon: Students work on individual projects, with Tim/Juan available to help and answer any questions  

### Course Materials
- [Pre-Course](https://github.com/black-tea/ucla-its-data-camp-2019/tree/master/Pre-Course)
- [Day 1](https://github.com/black-tea/ucla-its-data-camp-2019/tree/master/Day1)
- [Day 2](https://github.com/black-tea/ucla-its-data-camp-2019/tree/master/Day2)
- Day 3
- Day 4
- Post-Course

### Individual Project
Each student should plan to do an individual mini-project that should be completed shortly after the course concludes. You are free to work on this project during class (if you have already completed the in-class activites) or as homework after the day is complete. The project topic, goal, and data are all completely up to you; by the end of the first day you should be knowledgeable of a few different transportation datasets to help you get started.

In case you are stuck in coming up with ideas, below are a few ideas. Feel free to do any kind of mashup of the different datasets to produce some kind of insight.  
  
* Street Network Comparison: Compare the transportation networks of a couple different cities using Geoff Boeing’s osmnx python package. In what ways are they similar or different?
    * Data Source(s): [osmnx package](https://github.com/gboeing/osmnx)
* Collision Data: What can you find in the LA collision data that we didn't look at? How do collisions and neighborhood income intersect?
    * Data Source: [LA Collision Data](http://visionzero.geohub.lacity.org/), [CensusData Python package](https://pypi.org/project/CensusData/)
* SB 50 Analysis: There was a lot of news buzz around Scott Weiner's California [SB 50 bill](https://sf.curbed.com/2019/5/10/18563360/senate-bill-50-chart-sb50-explainer-housing-transit), which would upzone some neighborhoods based on transit accessibility. Which areas would be affected, and what are the characteristics of those neighborhoods?
    * Data Sources: [Metro GTFS Data](https://developer.metro.net/introduction/gtfs-data/download-metros-gtfs-data/), [CensusData Python package](https://pypi.org/project/CensusData/)
* LA Metro Real-time Data: Take a look at LA Metro’s developer APIs. Pick a couple of routes (or more) and periodically pull data for those routes every minute or so for at least an hour. What do you learn about those routes from the real-time data? 
    * Data Source(s): [Metro Realtime Vehicle Location API](https://developer.metro.net/portfolio-item/real-time-arrivals/), [osmnx package](https://github.com/gboeing/osmnx) 
* Mapping Commute Mode/Time: The American Communities Survey (ACS) provides estimates of cencus tract/block-level data on aspects of our commute. What can you learn about from visualizing this data? 
    *  Data Source: [CensusData Python package](https://pypi.org/project/CensusData/)
* Scooters & Neighborhood Characteristics: What can you learn about the types of neighborhoods that the scooters are being deployed in in Los Angeles? How does scooter density compare to the density or income of the neighborhood? Or, what can we learn about by comparing scooter location data and collisions?
    * Data Sources: [Scooter GBFS APIs](https://github.com/black-tea/swarm-of-scooters/blob/master/data/systems.csv), [CensusData Python package](https://pypi.org/project/CensusData/), [LA Collision Data](http://visionzero.geohub.lacity.org/)
* Scooter Operations: What do you learn about different scooter companies in the same city? (There are two good cities for comparing services within a city: Los Angeles and Washington, D.C.) Or, what do you learn about the operation of a scooter company across multiple cities? 
    * Data Sources: [Scooter GBFS APIs](https://github.com/black-tea/swarm-of-scooters/blob/master/data/systems.csv), [LA Collision Data](http://visionzero.geohub.lacity.org/)
* Exploring your own data: If you have a Google account, Google keeps track of you (unless you have specifically opted-out). You can get a dump of your own location data for as long as you've had an account with them and explore it to learn more about your own spatial-patterns via Google's Takeout Service.
    * Data Source: [Google Takeout](https://takeout.google.com/settings/takeout) _Note: You will have to wait up to a day to get your data generated by Google, so keep this in mind if you decide to procrastinate!_

#### this is another edit
