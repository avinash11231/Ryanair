# RYANAIR TEST AUTOMATION FRAMEWORK

Automating Ryanair Website to declined payment page using Cucumber + JUnit + Selenium 

## PREREQUISITE

Install JAVA on your machine and install plugins such as Cucumber, Natural and Maven on to Eclipse.

## INTRO

A valid Ryanair account holder with username and password mentioned in the Feature file, logs in to website
and books a ticket with invalid card credentials which is also mentioned in the feature file.
The payment transaction fails at the end and the error message is verified and logs are generated accordingly.
All the paramaterized values are taken from the feature file that gives all the data to perform the test.

## TECHNICAL DECISIONS

Using Cucumber since it was more favorable as per the test requirements (Please pardon if I did not use the 
standard norms since I have never worked using Cucumber earlier).
JAVA has been used to write the automation scripts since they are more preferrable. 
Feature files for each of the functionality has been created and repeated individually since it gives more 
easy information about the individual functionality.

The step definations have been done in a single page since it covers the entire scenario e2e.
The seperate feature files can be used to run tests on individual functionality if needed.

Please make sure to set the correct driver for the browser which is preferrable to run the test.

## PROCESS

The process is rather simple, you create a feature file for each page and a corresponding page object class.
Using the "Steps.java", implement all the methods required to run the test.

## RUN THE TEST

To run the test, use the testRunner package and change the feature file according to the test case needed to run.
To test the complete scenario, use the PaymentDetails.feature.
Right-click and run as JUnit.

Change the browser from config.properties file 
set browser=mac_chrome for Chrome Browser on MacOS
set browser=mac_firefox for Firefox Browser on MacOS

## REPORTS

Each time a test is run, logs are generated in the log folder. 
