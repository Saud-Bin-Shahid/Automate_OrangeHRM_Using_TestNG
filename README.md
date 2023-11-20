# Automate_OrangeHRM_Using_TestNG
This repository contains an automation script for Orange HRM websites. The script has been developed based on Selenium WebDriver and TestNG framework. The script covers all the possible test cases for running test automation on this site.

## Tools and Technology
- Java
- Intellij idea
- Gradle
- Selenium Webdriver
- TestNG

## Pre-requisites
- jdk
- gradle

## To Run This Project
- Clone this project
- Open terminal
- Give this following command for smoke test: gradle clean test -Pfilesuite="SmokeMasterSuite.xml"
- Give this following command for regression test: gradle clean test -Pfilesuite="RegressionMasterSuite.xml"
- For generating Allure Report use these commands: allure generate allure-results --clean -output & allure serve allure-results

## Test Cases
https://docs.google.com/spreadsheets/d/1zzuq4AYCDKwcbD-02MKu50W1btSHdOD7H3hMl4h0ISU/edit?usp=sharing
