# JMeter API Automation 

## Overview
This project is designed for the automation and testing of APIs, with a primary focus on understanding and evaluating the behavior of Restful APIs using HTTPS methods in Apache Jmeter version 5.5. Through automated testing, the project aims to ensure the reliability and correctness of API responses. By leveraging Groovy scripts, the project interacts with APIs, sending requests and validating responses.

## Software Requirements:
1. **Apache Jmeter**
2. **Jdk 8 or above**

## Project Setup:
1. Download Apache Jmeter 
2. Download Jdk 8.0 or above.
3. Clone the repository AutomateAPI.jmx
4. First open the Apache Jmeter by running jmeter.bat file in CMD or open Apache Jmeter Jar file
5. **Before running the test**: Change/define the path according to your local devices in the following JSR223 PostProcessor: (Below mentioned are Postprocessor's name)
   1. Modify Content ( Storing the modified content )
   2. Store the modified content in variable
7. **Running via GUI**
   1. Run Apache Jmeter by running jmeter.bat file in CMD or open Apache Jmeter Jar file
   2. Open the AutomateAPI.jmx (repository) from File->Open
   3.  "save it" and run
   4.  Results can be viewed in "View Results Tree" listener.
**8. Runnung via Command Line**
 1. Open Command Line and enter the command : jmeter -n -t path-existing-AutomateAPI.jmx -l path-to-generate-report.jtl and hti "ENTER"
 2. You can view the report .jtl in teh specified path.




