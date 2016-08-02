# project-with-pom-in-a-none-standard-location
This project simulates a client application in which the POM file is located in a different location (ie, in a subfolder in the workspace).

By default, the 'pom.xml' is found directly under the workspace.

In this app, the 'pom.xml is here:


    Workspace


    ----> actual-project
    
        ----> multi-module
        
        ----> single-module
        
        ----> pom.xml
