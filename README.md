JSF_EJB_JPA_Blank_Project  
==============================================================================================

O que é?
-----------
Projeto gerado no eclipse/jBoss Tools.

    JAVA EE 6 EAR
    MAVEN 3
    JBOSS 7 / WildFly
    JSF 2.0, CDI 1.0, EJB 3.1, JPA 2.0 and Bean Validation 1.0.

System requirements
-------------------

    SDK 1.6
    Maven 3
    JBOSS AS 7 ou WildFly

 
Build and Deploy
-------------------------

    mvn clean package jboss-as:deploy



Access the application 
---------------------

    <http://localhost:8080/teste-web>.


Undeploy
--------------------

    mvn jboss-as:undeploy


Arquillian Tests 
-------------------------

    mvn clean test -Parq-jbossas-remote 
