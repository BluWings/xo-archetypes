xo-archetypes
=============

This projects provides several Maven archetypes for [eXtended Objects framework](https://github.com/buschmais/xo) - XO for short. Those archetypes allows to quickly bootstrap a Maven project to develop an XO application. It currently uses the 0.4.0-SNAPSHOT version of XO.

xo-blueprints-quickstart
------------------------

The quickstart archetype creates a simple XO application using the [TinkerPop Blueprints](https://github.com/BluWings/xo-tinkerpop-blueprints) binding. To initiate the XO-Blueprints application call:

    mvn archetype:generate \
      -DarchetypeArtifactId=xo-blueprints-quickstart \
      -DarchetypeGroupId=com.smb-tec.xo.archetypes \
      -DarchetypeVersion=0.0.3-SNAPSHOT \
      -DgroupId=your.company \
      -DartifactId=my-xo-blueprints

Once generated, the application is ready to be built and test:

    cd my-xo-blueprints
    mvn clean verify

xo-neo4j-quickstart
-------------------

The quickstart archetype creates a simple XO application using the [Neo4j](https://github.com/buschmais/extended-objects) binding. To initiate the XO-Neo4j application call:

    mvn archetype:generate \
      -DarchetypeArtifactId=xo-neo4j-quickstart \
      -DarchetypeGroupId=com.smb-tec.xo.archetypes \
      -DarchetypeVersion=0.0.3-SNAPSHOT \
      -DgroupId=your.company \
      -DartifactId=my-xo-neo4j

Once generated, the application is ready to be built and test:

    cd my-xo-neo4j
    mvn clean verify

xo-orientdb-quickstart
----------------------

The quickstart archetype creates a simple XO application using the [OrientDb](https://github.com/BluWings/xo-orientdb) binding. To initiate the XO-OrientDb application call:

    mvn archetype:generate \
      -DarchetypeArtifactId=xo-orientdb-quickstart \
      -DarchetypeGroupId=com.smb-tec.xo.archetypes \
      -DarchetypeVersion=0.0.3-SNAPSHOT \
      -DgroupId=your.company \
      -DartifactId=my-xo-orientdb

Once generated, the application is ready to be built and test:

    cd my-xo-orientdb
    mvn clean verify

xo-titan-quickstart
-------------------

t.b.d.

License
-------

``xo-archetypes`` is contributed under Apache License 2.0.

Continuous Build
----------------

[![Build Status](https://secure.travis-ci.org/BluWings/xo-archetypes.png)](http://travis-ci.org/BluWings/xo-archetypes)