#Recipes for working with Receptiviti API


##Java

###Setup
How do I get set up?

####JDK 8

This is a Java project. So the first thing we need to care about is JDK (Java Development Kit) installation. Java 8 is the minimum required version for this project. Can be downloaded here: http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html

####Maven

Maven is a project builder normally used for most of Java projects. It is supported by all Java IDEs and it is possible to build and run Java applications with Maven directly from command line. Maven can be downloaded here: https://maven.apache.org/download.cgi. Minimal version we need is 3.0.5. Please follow installation instructions at the bottom of the page.

###Running Samples


    mvn test -DAPI_KEY=<Provide API KEY> -DAPI_SECRET_KEY=<Provide API SECRET KEY>