# clouseau

Clouseau uses Scalang to expose Lucene functionality via erlang-like nodes.

## Running a local dev cluster

In separate terminal windows, run each of these commands;

mvn scala:run -Dlauncher=clouseau1

mvn scala:run -Dlauncher=clouseau2

mvn scala:run -Dlauncher=clouseau3


## Build a jar

mvn package -Dmaven.test.skip=true

Then you can run the jar with: `java -jar clouseau-2.10.0-SNAPSHOT-jar-with-dependencies.jar`
