flink初体验

pre env
```
java8
maven3
flink 1.7x
```

1.单机启动Flink

```
   ./bin/start-cluster.sh
   look at  http://localhost:8081
```

2.运行任务在flink

```
mvn clean package
flink run /YOUR_PATH/xx.jar
```


3.更多例子
```

DataStream applications 数据流 todo
DataSet applications    数据集 todo
Table API / SQL queries 表API/SQL

```




