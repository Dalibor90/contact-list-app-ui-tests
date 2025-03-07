# contact-list-app-ui-tests
Contact List Application UI Tests with JAVA Selenium WebDriver

This project automates UI tests for the Contact List application using Selenium WebDriver and TestNG.

Prerequisites

Ensure you have the following installed before running the tests:

Java 8+

Chrome browser

ChromeDriver (ensure it matches your Chrome version)

Maven

TestNG (added as a dependency in the pom.xml if using Maven)

Setup Instructions

Clone this repository:

git clone https://github.com/your-username/contact-list-ui-tests.git

Navigate to the project directory:

cd contact-list-ui-tests

Update the chromedriver path in setUp() method of ContactListUITests.java if needed.

Install dependencies (if using Maven):

mvn clean install

Running the Tests

Using Maven (Command Line)

Run the tests using Maven:

mvn test

Alternatively, if using TestNG, run tests from the testng.xml file:

mvn test -DsuiteXmlFile=testng.xml

Using Eclipse

Import the Project into Eclipse

Open Eclipse → File → Import → Existing Maven Project.

Select the project folder and click Finish.

Ensure TestNG is Installed in Eclipse

Go to Help → Eclipse Marketplace.

Search for "TestNG" and install it.

Restart Eclipse if necessary.

Run the Tests in Eclipse

Open ContactListUITests.java.

Right-click anywhere in the file.

Select Run As → TestNG Test.

Test Scenarios Covered

UI Tests:

Login Test: Verifies login functionality with valid credentials.

Add Contact Test: Ensures a new contact can be added successfully.

Reporting

After execution, TestNG reports will be available in the target/surefire-reports directory.

Contributing

Feel free to fork this repository and submit pull requests for improvements or additional test cases.

License

This project is open-source and available under the MIT License.
