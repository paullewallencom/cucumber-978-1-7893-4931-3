AppiumTestAutomation With Cucumber-jvm
====================

This project exhibits how to combine BDD(Cucumber) approach with mobile automation. 

Prerequisite
=====================
1. Android SDK
2. Appium
3. Maven (For managing dependencies)
4. Gradle 
5. Eclipse (With TestNG plugin)

Installation
=====================
1. Install from git (using git clone)
2. Either Run `gradle check` from project directory
2. Or Run `mvn clean install` to use maven as build tool

Script Description
=====================
1. ApiDemoAppStepDefs:
	* apk Name: ApiDemos-debug.apk
	* apk Location: /src/test/resources
	* feature file Location: /src/test/resources/features
	* Type of Application: Native
	* Gesture Simulated: Swipe/Scroll
	
Integration with Jenkins
=====================
To be done

( **Note**: All scripts have been tested on real device (Nexus 5))

( **Note**: This is just reference project, hence defined feature file contains just basic Gherkins sentences.)