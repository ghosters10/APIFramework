# Cucumber BDD API Automation Framework
An API automation framework developed in BDD approach (Cucumber). It uses Java as a programming language. Gherkin syntax is also used as is the convention in a framework developed in behaviour driven development (BDD) approach. Some sample cases of add place, delete place and update place API of google maps has been written for demo purpose.

In order to use and run the framework, 
- Download all the files and folders in a parent folder. 
- Open this folder as a 'project' in Eclipse IDE.
- Open the file, 'TestRunner.java' in src/test/java/cucumber.Options package.
- Right click anywhere on the window > Run as > JUnit Test. OR Right click on POM.xml > Run As > 3 Maven build... > In Goals textbox, enter "test verify" > Click on Run

Following tool stack has been used for development of the framework.
- Language: Java
- Build Tool: Maven
- Test Data: Feature File (Handling with Excel and/or database can be implemented)
- Reporting: Currently, a report in JSON format is generated which can be converted into HTML reports online. Working on creating an HTML report automatically.
- Logging: Request and Response Logging Filter class.

The framework can be integrated with jenkins for CI/CD purpose.

