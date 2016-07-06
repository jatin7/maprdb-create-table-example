This is an extremely basic example of how to create a MapR DB table from Java.

You should have the `mapr-hbase` package installed, as this package provides the needed classes.

```
mvn package
java -cp `hbase classpath`:target/HBaseCreateTable-1.0-SNAPSHOT.jar com.mapr.example.CreateTable
```
