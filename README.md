# Neo4j-model
Datalake modelisation <br/>
Modelisation and implementation of the metamodel in a Neo4j environment for benchmark development.
<br/> <hr/><br/>

## Tools used
* Docker (Neo4j image pull)
* Jupyter Notebook (Python script for database implementation)
<br/> <hr/><br/>
## The metamodel
<img width="586" alt="metamodel" src="https://user-images.githubusercontent.com/82585768/140319195-a158224b-3051-47ea-8605-4a1b41fcd3c4.png">
The metamodel to implement
<br/> <hr/><br/>

## Translation UML to graph database
To make the best transformation possible, I decided to modelize the main relations between the nodes which are the most present on the diagram. <br/>
The following image summarizes it: <br/>
<img width = "586" img height = "680" alt= "Modelisation" src="https://user-images.githubusercontent.com/82585768/140326003-06355f89-193d-4a13-9d88-d901036cd62e.jpg">
<br/> <hr/><br/>

## Creation of the python script

The main library used: neo4j

    pip install neo4j
   
    from neo4j import GraphDatabase
