# Wildfire Detection And Burn Severity Analysis Using UAV And Satellite Imagery

## Problem Statement
Recently several wildfires have ravaged multiple countries for prolonged periods of time, destroying wildlife, imposing collateral damage and overall disruption of multiple natural and anthropogenic processes. The faster the fire is detected, lesser will be the consequent damages. A system that can promptly detect fires and alert the respective departments would be highly helpful. 

https://user-images.githubusercontent.com/62476858/167098586-dfb4a1fa-a302-4c37-a1a2-59cf04dd473c.mp4



---

## Personas of the System 
The application will be at the disposal of stakeholders like the fire department, disaster management units and NGOs that work with ecology conservation.

### Fire Department ###
Since timing is crucial in detecting wild fires, if the moment a fire starts and the fire department is alerted, they will have more time to control the situation. This will help in reducing the risk of death for both the fire fighters and the wildlife.

### Disaster Management Units ###
There could be human habitation near to where the fire starts. In such cases, it is important that disaster managemet teams are also alerted on the go, to avoid any fatalities.

### NGOs/ Ecological Enthusiasts ###
Wildfires are instrumental in destroying vegetation and breaking the rhythm of the ecosystem. Hence, it would be good to take immediate action to deal with the repercussions of a fire. Therefore, an alert can be sent to interested parties that would be able to take care of the situation promptly.

---

## Architecture

### Technical Architecture ###

![Technical Architecture](https://user-images.githubusercontent.com/62476858/167068755-ca265a94-acfa-496c-9620-f0cfd1aed81b.jpg)

The aim of this project is to host a trained deep learning model that detects wildfires. Each UAV will be surveilling the perimeters of it's assigned forest area. Once a fire is detected, an alert will be sent to the fire department along with the location of the UAV that detected the fire. Similarly, satellites can be used to regularly send burn severity analysis reports to the respective departments. 
_This repository consists of mainly three tasks:_
1. Wildfire detection from images 
2. Sending an alert if a fire is detected 
3. Burn severity analysis from satellite images.

### Technical Components ###
1. TensorFlow- To train the CNN architecture
2. Streamlit- Python based framework used for developing the web application
3. Google Earth Engine API- To connect to Earth Engine service automatically
4. Folium- A python library to create several types of leaflet maps.
5. Selenium- An open-source tool that automates web browsers.
6. PIL- Python Image library for dealing with images
7. OpenCV- for real-time Computer Vision
8. SMTP- Python module for sending emails using Simple Mail Transfer Protocol

##Demo Video
[Click Here for Demo Video](https://drive.google.com/file/d/1lUafUNnWvHUzRvg5HPDCeUtFBeMGGw7j/view?usp=sharing)


![code mail](https://user-images.githubusercontent.com/62476858/167107156-4cb8c0a0-de97-4e8f-b571-7b8d15fe268d.jpeg)

![mail](https://user-images.githubusercontent.com/62476858/167107124-8fdd4394-a078-4105-affa-ae1f9ec12426.jpeg)

---

##Contributors
1. Reshma Santhosh
2. Ananya Ayasi
