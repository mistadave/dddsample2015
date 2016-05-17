# DDDSample
This is the new home of the original DDD Sample app hosted at SourceForge. 

Our intention is to move everything from SourceForge to GitHub in due time while starting upgrading both the technical aspects as well as the DDD aspects of the DDD Sample.

Discussion group: https://groups.google.com/forum/#!forum/dddsample

Development blog: https://citerus.github.io/dddsample-core/

Trello board: https://trello.com/b/PTDFRyxd

[![Build Status](https://travis-ci.org/citerus/dddsample-core.svg?branch=master)](https://travis-ci.org/citerus/dddsample-core)

## Build DDD Sample

To build the DDD Sample project you need first to build the project.

```
mvn clean package
```

## Rund DDD Sample

The command to run the project after the build.

```
mvn jetty:run
```