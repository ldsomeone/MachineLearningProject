# Machine Learning Project
## Supervised and Unsupervised Learning

<br>

### Table of Contents
- [Description](#Description)
- [Coding](#Coding)
- [Worklog](#Worklog-and-Commits)
- [References](#References)

<br>

### Description and Purpose:

Overview: This project uses an ESP-32, DHT-11 (Weather) Sensor and HR-S04 (Ultrasonic) Sensor to take readings on the weather and capacity of a water tank. This data is transfered over WiFi to the server so that you can check the weather and how much water is left in your tank at any time. This is useful so you can manage your water use and this project is the start of a fully automated watering system. This is because there is the potential to develop this idea a lot further with a rain-sensor model, soil moisture or an irrigation controller. 

Purpose: This is designed to be the start of a fully automated IoT watering system.

Usage: This project is intended so that the ultrasonic sensor is placed on top of a water tank (with a powersource) and taking in data once every few minutes. It, combined with the weather sensor will transmit data over the WiFi to the server where you can chech the status at any time. It is also possible to do so while away or on holidays so that your garden will stay looking great!

Important: All of the code has been commented for easy understanding. In the firmware folder, in the arduino code (.ino) file, you will have to change the network name and password to whatever you want (your WiFi) because otherwise this project will not work.

<br>


### Setting Up A Github Repository
Setting up a GitHub repository can be very useful so you have a record of your code.
<br>
A step-by-step guide is detailed below, but to fork this repository and get started straight away, follow the link: [How to Fork a GitHub Repository](https://docs.gitlab.com/ee/user/project/repository/forking_workflow.html)

1. Create a GitHub Account:
    > If you don't already have a GitHub account, you'll need to sign up for one. Go to https://github.com/ and follow the instructions to create your account.
2. Create a New Repository:
    > Once you're logged in, click on the "+" sign in the upper right corner of the GitHub page and select "New repository". Then follow the prompts.
3. Initialise with a README:
    > If your project doesn't already have a README file, it's a good practice to check the "Initialize this repository with a README" option. A README provides information about your project and is a great place to document how to use your code.
4. Create Repository:
    > Click the "Create repository" button. Your new repository will be created, and you'll be directed to the repository's main page.
5. Set Up Local Git Configuration:
    > If you haven't already configured Git on your local machine, follow the instructions in the GitHub repository to set up your Git identity (username and email). This is essential for committing and pushing changes from your local machine to the remote repository.
6. Push Code:
    > If you have existing code you'd like to add to your repository, follow the instructions on the repository page under "…or push an existing repository from the command line." This will guide you through the process of connecting your local Git repository to the remote repository on GitHub.



<br>

### Development Roadmap

- [x] Setup repos - GitHub
- [x] setup ESP32 - Arduino IDE
- [x] Install dependencies - aREST.h and DHT.h
- [x] Test ESP32 - get json data via wifi
- [x] Initialize Node.js environment
- [x] setup server.js with express
- [x] set index route and views
- [x] link ESP32 to Node app with fetch

<br>

### Coding
This is the rough process I used to code the project. This can all be seen in the actual files in this repository.

1. Import all the libraries.
    > 

    >


<br>

### Worklog and Commits

Date | Commit Message | Version
:-----|:----------------:|:--------:
02.08.24 | initial setup of repository | 0.1.0
00.00.00 |   | 0.1.1


<br>

### References

- The Website Architech (2021). How to Layout a Webpae [https://www.youtube.com/watch?v=3C_22eBWpjg](https://www.youtube.com/watch?v=3C_22eBWpjg)
  
- Fireship (2021). JS Native Fetch. [https://www.youtube.com/watch?v=MBqS1kYzwTc](https://www.youtube.com/watch?v=MBqS1kYzwTc)
  
- W3 Schools (2023). Node JS Introduction. [https://www.w3schools.com/nodejs/nodejs_intro.asp](https://www.w3schools.com/nodejs/nodejs_intro.asp)
  
- Components 101 (2021). HC-SR04 Ultrasonic Sensor. [https://components101.com/sensors/ultrasonic-sensor-working-pinout-datashee](https://components101.com/sensors/ultrasonic-sensor-working-pinout-datasheet)
  
- Instructables (2021). Water Level Indicator Using a HC-SR04 [https://www.instructables.com/Ultrasonic-Water-Level-Indicator-Using-HC-SR04-Ard/](https://www.instructables.com/Ultrasonic-Water-Level-Indicator-Using-HC-SR04-Ard/)

- Components 101 (2021). DHT-11 Temperature Sensor. [https://components101.com/sensors/dht11-temperature-sensor](https://components101.com/sensors/dht11-temperature-sensor)
  
- Circuit Bread (2019). How LED's Work and How to Control Their Color. [https://www.circuitbread.com/tutorials/how-rgb-leds-work-and-how-to-control-color](https://www.circuitbread.com/tutorials/how-rgb-leds-work-and-how-to-control-color)
  
- LogRocket (2021). How to Use EJS to Template Your Node Application. [https://blog.logrocket.com/how-to-use-ejs-template-node-js-application/](https://blog.logrocket.com/how-to-use-ejs-template-node-js-application)

