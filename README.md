Java Pet Store Sample
=============

This is a Java sample using the Spring framework. This application uses a java
buildpack.


Building the Application
------------------------

To build the application, make sure you have [Maven](http://maven.apache.org/ "Maven") installed.
Then, *cd* into the root directory and execute:

	mvn clean package

That will create the *jpetstore.war* file in the 'target' directory.

Deploying the Application
-------------------------

To deploy to HPE Helion Stackato:

    mvn clean package 
    stackato push -n

You can view the application at the 'Application Deployed URL'.
