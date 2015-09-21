devopsbackend
-------------

DevOpsBackend uses Google Cloud Endpoints for creating a REST API

The instructions at the following link were used as reference :

https://cloud.google.com/appengine/docs/java/endpoints/getstarted/backend/helloendpoints

Using .gitignore from here

https://github.com/GoogleCloudPlatform/appengine-endpoints-helloendpoints-java-maven/blob/master/.gitignore

Step1 :

//----------------------------------

In a terminal window, change to the directory where you want to build the project.

Invoke the following Maven command:

mvn archetype:generate -Dappengine-version=1.9.26 -Dfilter=com.google.appengine.archetypes:
Enter the number 4 to select the remote -> com.google.appengine.archetypes:hello-endpoints-archetype from the list of App Engine archetypes.

Select the most recent version from the displayed list of available archetype versions by accepting the default.

When prompted to Define value for property 'groupId', you can supply a namespace of your choosing, 
but if you want to keep this tutorial in sync with the source files on GitHub, use com.example.helloendpoints. 
(The typical convention is to use a namespace starting with the reversed form of your domain name.)

When prompted to Define value for property 'artifactId', supply the project name helloendpoints.

Accept the defaults for the remaining prompts.
//----------------------------------
