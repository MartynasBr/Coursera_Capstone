# Coursera_Capstone
This notebook will be used to create Coursera capstone project.
1. Introduction
1.1 A description of the problem and a discussion of the background
Did you know? IBM Watson Studio lets you build and deploy an AI solution, using the best of open source and IBM software and giving your team a single environment to work in. Learn more here.
Serious situation with COVID-19 in the world should change travel habits. More people will start to avoid public transport, because of possibility to get sick. So some of them will start to travel to work on feet or by bike.

Another reason, which will eventually change travel habits is the fact that the world is getting greener. People understand that they has to do something to reduce co2 emmission. Of course some of them is starting to use electric car, however, some people choose to travel on foot or by bike.

I will use Collisions data from Seattle city to generate a few most worrying neighborhoods based on my criteria.

1.2 A description of the data and how it will be used to solve the problem.
Based on definition of my problem, factors that will influence our decission are:

number of collisions, which includes pedestrians and bicycles.
additional factors may have contributed to the cillisions (weather, road condition, light condition and etc.)
seriousity of collisions.
I decided to use regularly spaced grid of locations, centered around city center. Also, I will use various Machine Learning methods to analyze data and find

Following data sources will be needed to extract/generate the required information:

ArcGIS Metadata Form of all year collisions data set from Seattle city.
