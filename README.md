# Template / Starter App for Kafka Streams

## Goals

To provide a starter project for Kafka Streams with Scala.  It includes:
* Working "pipe" stream processor, ready to be added to.
* Configuration via pureconfig
* Logging with scala-logging
* unit-testing of streams via mockedstreams
* Json handling with Json4s
* Fat jar support via assembly plugin

## To Use

### Run

```
sbt test run
```

### Build Jar

```
sbt assembly
```

### To Rename Project 

To use this as a starter project, you can run the 'renameproject.sh' script as follows:

```
./renameproject.sh new-project-name -p $NEW_PACKAGE_PREFIX
```
...where NEW_PACKAGE_PREFIX is "com.mycompany.myproject" or something like that.

For help running the script, please type: 

```
./renameproject.sh -h
```
