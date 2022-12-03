# S2 Geometry Library for Java 8
This reporsitory is a copy of https://github.com/google/s2-geometry-library-java
with mininal changes to make it compile and run under Java 8 environment.

## Build
Run the following command:
```
docker run -it --rm -v $PWD:/src -w /src maven:3.8.6-openjdk-11
```

Once the above command is done, the output can be found under `library/target/s2-geometry-library-HEAD-SNAPSHOT.jar`

## Differences

Check [patch.diff](https://github.com/igorgatis/s2-geometry-library-java-8-backport/blob/master/patch.diff) file for the list of changes.
