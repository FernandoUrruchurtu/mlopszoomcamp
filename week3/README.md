# Week 3: Orchestation

In this week we're going to orchestate a mlops environment using Mage.AI.

First of all we create a project named homework_03.

- The version that we are running is v0.9.70,
- The yaml have 55 lines.

- In order to load our data files, we have two options: 
1. load from Github on our repository
2. Copy to the docker image.

We choose the second option where first we moved to the data path and then copy the file to docker: docker cp yellow_tripdata_2023-03.parquet 1bb776cbc5bc:/home/yellow_tripdata_2023-03.parquet

