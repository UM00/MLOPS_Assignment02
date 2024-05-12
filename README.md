Last Assignment of FAST NUCES 2020-2024


![fast logo](https://github.com/UM00/MLOPS_Assignment02/assets/113986416/3281c1ab-6eeb-40ef-8e92-84d3e891c083)



THe Assignment was about Airflow in which we were to write a Dag script 

To automate the process of Exctracting Transforming and Then using the DVC to store tha data and do its versioning

First and foremost we configure the Airflow using Docker to load its Docker image


![Container](https://github.com/UM00/MLOPS_Assignment02/assets/113986416/15b74cc1-f418-4eff-a371-758f363ae31a)



Then running it on a container locally

Then we write our Dag scripts to automate the whole process

![Mlops_Assignment_02 success Airflow](https://github.com/UM00/MLOPS_Assignment02/assets/113986416/e4d2b3ad-3dd9-4098-bff5-efad6b2805c3)

Here is the successful working of Dag script

![GanttChart](https://github.com/UM00/MLOPS_Assignment02/assets/113986416/ce5d3ce3-829f-4f19-af11-3dd47a9567c5)

![Airflow Report](https://github.com/UM00/MLOPS_Assignment02/assets/113986416/ad0b1af9-21b7-4ab1-a832-48df3d24a548)

Problems Faced


If we talk about problems the first and foremost would be 

Module Import 

The Dag file couldn't find the required resource like libraries for its functioning ultimately causing the whole script to fail

Solution


![solution](https://github.com/UM00/MLOPS_Assignment02/assets/113986416/9e738445-e840-4887-ab06-bf72bfa80418)


The solution we came up with was to build an image with the modules that Dag file couldn't find
In this way we proceeded forward
