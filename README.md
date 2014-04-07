xo-archetypes
=============

This projects provides several Maven archetypes for eXtended Objects. Those archetypes allows to quickly bootstrap a Maven project to develop an XO application.

These artifacts are based on the XO framework (https://github.com/buschmais/xo). It currently uses the 0.3.0-SNAPSHOT version.

xo-neo4j-quickstart
-------------------

The quickstart archetype creates a simple XO application using the Neo4j binding. To initiate the XO-Neo4j application call:

	mvn archetype:generate \
      -DarchetypeArtifactId=xo-neo4j-quickstart \
      -DarchetypeGroupId=com.smbtec.xo.archetypes \
      -DarchetypeVersion=0.0.1-SNAPSHOT \
      -DgroupId=your.company \
      -DartifactId=my-xo-neo4j

Once generated, the application is ready to be built and test:

    cd my-xo-neo4j
    mvn clean verify
