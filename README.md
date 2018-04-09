# AUBKiosk
Description: An application accessed via a touch screen/kiosk, featuring an interactive 3D map of AUB’s (the American University of Beirut) campus, designed to help users find their way around campus, or search for important university-related information such as places to eat (on and off-campus), places to study, people, specific buildings, classrooms and departments.

Background and motivation: We are three AUB students who had difficulty navigating through campus and finding our classes when we first came to the university. Hence, we decided to create this 3D map to help new students virtually navigate the university and get familiar with the campus without having to physically attend the campus. In addition, that was our final year project for our undergraduate degree. We also won the final year project award with this project.

A [trailer video](https://youtu.be/8zhAN19fM0A) was also created to communicate our motivation.

# Features
* 3D navigation through campus
* Search bar: The ability to search for information about people, buildings, study places, and departments.
* Pins: 3D pins marking notable locations on campus (vending machines, cafeterias, libraries...)
* Study on campus: Finding empty available classrooms for studying at any time during the day
* Off campus: Providing information about restaurants and places to eat in the neighborhood around campus.
* Path: Plotting the fastest walking route from the kiosk (where this application is installed) to any place on campus.

# Technical description
We used SketchUp to create the 3D models. Then imported these models to Unity and used them to create an application where a user can freely navigate the map. We also added the features above via C# programming in Unity. In addition, a Java web-scraper was used to collect data from university and touristic (zomato.com) websites in order to load the database.

More general and technical documentation can be found in our **documentation repository**.

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
This repository does not contain all the files needed to create this project. Since Unity has large files that exceed the max file size that we can upload to Github. The Unity project can be found on [this link](https://mailaub-my.sharepoint.com/:u:/g/personal/sha57_mail_aub_edu/EcynrOQpkktLgnvGehTvXq0BVsiZigu9qMEF8Hf8HZlIyQ?e=J71dIV).