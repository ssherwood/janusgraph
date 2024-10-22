# 

To build an instance of JanusGraph using the YugabyteDB drivers:

```shell
mvn clean install -Pjava-11 -Pjanusgraph-release -Puse-yugabytedb -DskipTests=true --batch-mode --also-make -Dgpg.skip=true
```