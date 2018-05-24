# AUBKiosk
Description: An application accessed via a touch screen/kiosk, featuring an interactive 3D map of AUB’s (the American University of Beirut) campus, designed to help users find their way around campus, or search for important university-related information such as places to eat (on and off-campus), places to study, people, specific buildings, classrooms and departments.

Background and Motivation: 
We are three AUB students who had difficulty navigating through campus and finding our classes when we first came to the university. Which is why we decided to find a solution, a 3D map of the University to help new students virtually navigate the campus and get familiar with it without having to be physically there. 
This project was done in the context of our Bachelor Final Year Project(FYP) at the American University of Beirut (AUB).
Our team won the Murex Best Innovative Development Project (2015-2016).
https://website.aub.edu.lb/fas/fas_home/student-resources/Pages/best-computerscience-project.aspx

A [trailer video](https://youtu.be/8zhAN19fM0A) was also created to communicate our motivation.

# Features
* 3D navigation through campus
* Search bar: The ability to search for information about people, buildings, study places, and departments.
* Pins: 3D pins marking notable locations on campus (vending machines, cafeterias, libraries...)
* Study on campus: Finding empty available classrooms for studying at any time during the day
* Off campus: Providing information about restaurants and places to eat in the neighborhood around campus.
* Path: Plotting the fastest walking route from the kiosk (where this application is installed) to any place on campus.

# Technical description
We used SketchUp and Blender to create the 3D models. Then we imported these models to Unity and used them to create an application where a user can freely navigate the map. We also added the features above via C# programming in Unity. In addition, a Java web-scraper was used to collect data from university and touristic (zomato.com) websites in order to load the database.

More general and technical documentation can be found in our [documentation repository](https://github.com/samasri/AUBKiosk/tree/master/Documentation).

# Demo
This [demo video](https://youtu.be/5xD5sSZjJlE) shows all the features of the project. However, it was only intended as a visual aid when presenting the project and hence it has no sound at all.

# Directories description:
* **Presentations**: Contains presentations we did for our project in the univeristiy.
* **Documentation**: Contains technical and formal report that we wrote about the project.
* **Facilities Planning and Design Unity - Dimensions and Pictures**: Dimensions and other information we got about university buildings; in order to have the more accurate 3D models.
* **Pictures**: Pictures we took about university buildings in order to create 3D models for them.
* **Database**: Contains information collected from the university and touristic websites. We used this information to build the database of the project in order to get information such as neighborhood restaurants and empty classes available for private studying. Due to uploading this project on Github after its development in few years, we were not able to reproduce all the files needed to create the database.
* **Buildings**: Contains 3D models we created (via sketchup) for AUB buildings.

# Disclaimer
This repository does not contain all the files needed to rebuild the project. Since Unity has large files that exceed the max file size that we can upload to Github. The Unity project can be found on [this link](https://mailaub-my.sharepoint.com/:u:/g/personal/sha57_mail_aub_edu/EcynrOQpkktLgnvGehTvXq0BVsiZigu9qMEF8Hf8HZlIyQ?e=J71dIV).
