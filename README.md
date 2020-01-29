# apacheSpark

Spark : engine for large-scale data processing

|                               |     |
| ----------------------------- | --- |
| 1. Intro                      |     |
| 2. Scala                      |     |
| 3. Spark Basic                |     |
|                               |     |
| 4. Spark Programs             |     |
| 5. Running Spark on a cluster |     |
| 6. SparkSQL                   |     |
|                               |     |
|                               |     |
|                               |     |
|                               |     |
|                               |     |
|                               |     |

## Spark

- engine for large-scale data processing
- scalable : driverProgram(SparkContext) -> ClusterManager() -> Executor(cache, task)
- Spark Core -> streaming, SQL, MLlib, GraphX

- Resilient Distributed Dataset : tolerant, split
- Transform RDD(map...),  Actions(collect, count...)

