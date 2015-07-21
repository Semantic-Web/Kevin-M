This is my assignment 7 on GeoNames.

***** OVERVIEW *****
For this assignment I wanted to find the current weather information for certain locations found within the GeoNames databases. In order achieve this java was used. I used the Eclipse IDE for the code development. The GeoNames JAVA CLIENT was used in order to query the GeoNames databases and retrieve the wanted information.

The problem this application solves is that it provides the site and weather information availble from the GeoNames database for a given International Civil Aviation Organization(ICAO). ICAO codes are 4 digit codes. 

To demonstrate the functionality of this application I have also included a .pdf file with screenshots of my input and output. I retrieved the following site information:

                      1. Station Name
                      2. Country Code
                      3. Latitude & Longtitude Coordinates

In addition the following weather information was retrieved:
 
                      1. Observation Time
                      2. Cloud Information
                      3. Temperature
                      4. Humidity
                      5. Wind Speed
                      6. Dew Point
                            
The information above was found for 9 ICAO sites. They were all airports. Therefore, ICAO airport codes were used. From the 9 sites used 5 were US sites and 4 were international sites.

***** INSTRUCTIONS TO RUN THE APPLICATION *****
In order to run the application the following steps need to be performed before running the application:

                        1. Create a username from the following link http://www.geonames.org/login
                        2. Enter username in setUsername() in main()
                        3. Enable web services for your username
                        4. Download the GeoNames .jar http://www.geonames.org/source-code/geonames-source-1.1.12.jar
                        5. Download the JDOM .jar http://www.geonames.org/source-code/jdom-1.0.jar
                        6. Add the GeoNames and JDOM libraries to the build path of the project.
                  
To run the application click the run button and enter the "ICAO" code in the pop-up window. Click enter and the results are shown in the application console. 

NOTE: If the ICAO code is not found inside the GeoNames database the results will be "ICAO Code Not Found".

The program needs to be terminated to exit.
