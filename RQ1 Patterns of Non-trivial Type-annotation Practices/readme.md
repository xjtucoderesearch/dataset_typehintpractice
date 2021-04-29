# RQ1 data
This folder illustrates data corresponding with the RQ1.
##  InconsistentClasses
The **InconsistentClasses** folder contains two sub-folders.  
The **InconsistentClasses(sub)** enumerates the new class defined in the stub file but not in the corresponding source.  
The **InconsistentClassInherit** folder includes all the baseclass-subclass pairs related to these inconsistent classes.

## InconsistentFunctions
The **InconsistentFunctions** folder contains, for each project, functions that exist in stub files but doesn't match an implementation in the corresponding source.

## InconsistentStubs
A project may contain some stub files which don't have a corresponding source file.
The **InconsistentStubs** folder lists stub files that don't have a corresponding source.

## OverloadedFunctions
The **OverloadedFunctions** folder includes the number of overloading type implementation and their overloaded number. If there exists an overloading type implementation in such a project, the function which has the maximum overloaded number is also listed.
## Protocols
This folder contains three sub-folders and a csv file.  
The **ProtocolUse.csv** contains the number of protocols and their implicit or explicit implementation for each project.
The **Protocols(sub)** folder lists all protocol definitions for each project.   
The **Implicit** and **Explicit** folders list their implicit and explicit implementation respectively.