
# ShareBuyTestFramework
A maven selenium test framework written in java to test features of buyshares.co.uk website with Extent Reports for test results.

## Prerequisites
For building and running the application you need:
* [JDK](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
* [Maven](https://maven.apache.org/download.cgi?Preferred=ftp://ftp.osuosl.org/pub/apache/)
* [IDE - IntelliJ](https://www.jetbrains.com/idea/download/#section=windows)
* [ChromeDriver](https://https://chromedriver.chromium.org/downloads)

## Getting Started 
Copy the repo into your local machine.

### Running the tests locally

Open the project in IDE right-click the `testng.xml`and select "Run" or "Debug" to start the tests.

#### Run tests through the commandline

As this project uses Maven, we can invoke the tests using Maven from our commandLine.

To run the test:
- open `cmd`  
- `cd` to your project root folder in command line.
- run `mvn clean compile test` 

### Reports
Extent Reports for each test run can be found in - `\BuySharesTestFramework\reports`

### Set up
1. Clone the repo into your local machine.

2. Download:
- [IntelliJ](https://www.jetbrains.com/idea/download/#section=windows) (IDE to run tests and debug)
- [ChromeDriver](https://https://chromedriver.chromium.org/downloads) corresponding to your Chrome browser version and place in `%PATH%\BuySharesTestFramework\driver`

3. Set Path for Java and Maven in environment variables
* JAVA_HOME: `%PATH%\Java\<jdkversion>`
* M2_HOME: `%PATH%\<mavenversion>`
* Add to PATH: `%M2_HOME%\bin` and `%JAVA_HOME%\bin` 

### Edit the test script
To edit the script in GUI mode run in powershell - `EditTestInJmeter.ps1`
### Configure test parameters
Test parameters can be configured using file - `test.properties`
### Data creation
Before starting load test we need to set up initial data. Run `DataCreation.ps1` to create some accounts to begin with.
### Run load tests
To start a load test run in powershell - `StartLoadtest.ps1`

Built With:

- Selenium - Browser automation framework
- Maven - Dependency management
- TestNG - Testing framework
- Extent Reports - Reporting framework
