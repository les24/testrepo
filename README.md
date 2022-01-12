
# ShareBuyTestFramework
A maven selenium test framework written in java to test features of buyshares.co.uk website with Extent Reports for test results.


## Prerequisites
For building and running the application you need:
* [JDK](https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html)
* [Maven](https://maven.apache.org/download.cgi?Preferred=ftp://ftp.osuosl.org/pub/apache/)
* [IDE - IntelliJ](https://www.jetbrains.com/idea/download/#section=windows)
* [ChromeDriver](https://https://chromedriver.chromium.org/downloads)

## Running the tests locally

Open the project in IDE right-click the `testng.xml`and select "Run" or "Debug" to start the tests.

#### Run tests through the commandline

As this project uses Maven, we can invoke the tests using Maven from our commandLine.

To run the test:
- open `cmd`  
- `cd` to your project root folder in command line.
- run `mvn clean compile test` 

