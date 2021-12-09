# java-cli-maven-spring-surefire-findbugs-testng-test-car-data

## Description
Analyze source code for potential bugs.
A POC for spring app using testng
framework with surefire plugin.

## Tech stack
- java
- maven
	- findbugs
  - spring
  - testng
  - surefire

## Docker stack
- maven:3-openjdk-17

## To run
`sudo ./install.sh -u`
- findbugs report at bin/target/findbugs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://github.com/eugenp/tutorials/tree/master/testing-modules/testng)
