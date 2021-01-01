# Calculator
Calculator.java multiplies and divides.<br />
CalculatorTest.java tests Calculator's methods using JUnit.<br /><br />
To compile and run, _cd_ to _/Calculator_ and type **_ant -f build.xml_** on a shell, after taking the following prerequisite steps:<br />
* Install Ant from http://ant.apache.org/.
* Configure your _ANT_HOME_ environment variable to reference the topmost directory of the Ant distribution.
* Configure your _PATH_ environment variable to reference _ANT_HOME_ in a relative manner, by including _PATH=%ANT_HOME%\bin;_ for Windows or _PATH=$(ANT_HOME)/bin:_ for Linux.
* Download the JUnit 5 JAR files from https://junit.org/junit5/.
* Configure your _JUNIT_ environment variable to point to the directory containing those JAR files.

JUnit API JAR files
* junit-jupitar-api.jar
* junit-jupitar-engine.jar
* junit-jupitar-params.jar
* apiguardian.jar
* opentest4j.jar

JUnit Platform JAR files
* junit-platform-commons.jar
* junit-platform-engine.jar
* junit-platform.launcher.jar
* junit-platform-runner.jar:
* junit-platform-suite-api.jar
