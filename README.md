# Check-Toxicity-in-comments

Check Toxicity in comments is a simple web application built using python flask and REST API, where it checks and judges the if there is any toxicity in the given comment

In this web application we used AI model that was trained with JIGSAW data. To persist the data MongoDB was used in the backend

All dependencies in the project was virtualized using Docker and containers


![alt tag](https://github.com/pothabattulasantosh/Demo_App/blob/master/Screenshot%20from%202020-07-22%2015:21:44.png?raw=true)

### Before running this App:

##### 1.Since this app was developed in Ubuntu OS, please make sure you have Linux keranl based OS (Eg:Ubuntu,CentOS).
##### 2.Read Docker prerequisites (please visit [here](https://docs.docker.com/engine/install/)) and install Docker in your OS.

### To Run this APP:

##### 1. Clone this repo into your system
```bash
 $ git clone https://github.com/pothabattulasantosh/Check-Toxicity-in-comments-WEB-APP.git
 ```
##### 2. Go to Demo_App directory
```bash
 $ cd Demo_App
 ``` 
##### 3. Now create a docker Build for this application.

```bash
 $ sudo docker-compose build
 ``` 
##### 4. Now Up the application.

```bash
 $ sudo docker-compose up
 
``` 
##### After few seconds you can access this Application at http://0.0.0.0:5000 or http://<your serverIP/DNS>:5000



