## Simple EDI Transormation 

Given the complexity in many healthcare EDI transactions, it is sometimes tedious to process the EDI transactions without investing in an expensive transformation engine.  This project attempts to simplify that process by using simple open source tools to create java project that allows you to start processing healthcare transactions.

We will create a simple application using the open source smooks library to transform healthcare EDI transactions to XML and vice versa.

### Main Libraries Used

1.  Smooks  :-  We use [Smooks framework](http://www.smooks.org/) to build and transform data from XML and non XML data (CSV, EDI, Java etc) using Java.
2.  Maven   :-  We use [Apache Maven](https://maven.apache.org/) for dependency and build management. 
3.  Camel   :-  We use [Apache Camel](http://camel.apache.org/) to define routing and mediation rules.

We use additional libraries as defined in the pom to support ancillary tasks within the application.


## Running application locally

First, you will have to download it. If you have a local installation of git, you can do it by simply cloning this repository:
```
git clone https://github.com/nnjora/health-care-transformation.git
```
If you don't have git installed, you can download a .zip by pressing on the Download zip button in the upper side of this page.

Once downloaded, the application can be locally started with:
```
mvn tomcat7:run
```
