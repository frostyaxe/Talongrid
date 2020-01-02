# Talongrid
Talongrid is a utility written in java that allows you to configure the selenium grid automatically on the local machine. In this repository, you will get the required files to start with the Talongrid.

## Installation

Use [git bash](https://gitforwindows.org/) to pull the code from github repository.

## Features
* It allows you to start the selenium grid on your local machine easily just by running a simple command.
* It can dynamically increase or decrease the selenium grid node instances based on the requirement.
* Simple configuration file is required to handle the selenium grid configuration.

## Prerequisites
* JDK 1.8


## Usage

```bash
1. Navigate to folder containing the Talongrid files.
2. Execute below command with java.exe( JDK 1.8 )
    * java -jar talongrid-<ver>.jar
      Example: java -jar talongrid-1.0beta.jar
```

## Configuration 
Talongrid requires a configuration file to read the details related to configure selenium grid. This configuration file is present in config folder. 

Below are the properties that must be present in the configuration folder:
* grid.hub.ip: This property helps the
user to set the IP address of selenium grid hub.
   For example: grid.hub.ip = localhost
* grid.hub.port: This property allows the user to specify the port for the selenium grid hub.
   For example: grid.hub.port = 4444
* grid.node.port: This property helps the user to set the port of the selenium grid node instance.
   For example: grid.node.port = 5556
   
   
In order to set the webdrivers for selenium grid node web browser instances, you will have to use the key value pair as shown below.
* webdriver.chrome.driver = \<chromedriver path>
* webdriver.ie.driver = \<Internet Explorer path>
* webdriver.gecko.driver = \<gecko driver path>

## Authors

* **Abhishek Prajapati** - [Talongrid](https://github.com/frostyaxe/Talongrid/tree/release/talongrid_1.0Beta)

## Support
Reach out to me at one of the following places!

* Gmail: prajapatiabhishek1996@gmail.com
* Facebook: www.facebook.com/rapperabstar

## License
* Copyright 2015 © [Frostyaxe](https://github.com/frostyaxe)
