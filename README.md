# LoadTest-with-jMeter

## Requirements
The following requirements exist for running Apache JMeter:

- Java Interpreter:
  A fully compliant Java 8 Runtime Environment is required
  for Apache JMeter to execute. A JDK with `keytool` utility is better suited
  for Recording HTTPS websites.

- Optional jars:
  Some jars are not included with JMeter.
  If required, these should be downloaded and placed in the lib directory
  - JDBC - available from the database supplier
  - JMS - available from the JMS provider
  - [Bouncy Castle](https://www.bouncycastle.org/) -
  only needed for SMIME Assertion

- Java Compiler (*OPTIONAL*):
  A Java compiler is not needed since the distribution includes a
  precompiled Java binary archive.
  > **Note** that a compiler is required to build plugins for Apache JMeter.

## Installation
To download and install Katalon Studio, visit the website: https://www.katalon.com/katalon-studio/](https://jmeter.apache.org/download_jmeter.cgi
- You can choose Source download or if you can open the jMeter you can choose Binaries download

## Running JMeter
1. Change to the `bin` directory
2. Run the `jmeter` (Un\*x) or `jmeter.bat` (Windows) file.




