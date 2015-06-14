h2-weblogic12c-datasource-example
=====================

Example application showing the use of H2 database in Oracle Weblogic 12c.

To create the project,

just run the command below:

mvn eclipse:eclipse

Or import it into eclipse using Import -> Existing Maven Projects.

It will create the eclipse project.

To build the project, run 

mvn clean install

To deploy it in Weblogic, first you have to add the H2 jar into Weblogic 12c and then create a datasource named datasource.h2 (the datasource name is configurable in the properties file).
Then just deploy the war into Weblogic 12c.

The full explanation is in my blog:
 https://andreiribas.wordpress.com/2015/05/09/installation-and-use-of-h2-database-in-a-connection-pool-on-oracle-weblogic-12c-application-server/
