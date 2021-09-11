

# Individual Part Paper Reading List


## 1.query optimization

### 1.1 overview
- [x] What’s Really New with NewSQL?(Andrew Pavlo,recommended)
- [ ] Ioannidis, Y. E. (1996). Query Optimization. ACM Computing Surveys, 1–38.
- [ ] Surajit Chaudhuri.An Overview of Query Optimization in Relational Systems
- [ ] An overview of parallel query optimization in relational systems

### 1.2 query optimizer implement
- [x] ORCA:A modular query optimizer architecture for big data (recommended)
- [x] The MemSQL Query Optimizer:A modern optimizer for real-time analytics in a distributed database (recommended)
- [x] Query Optimization Time: The New Bottleneck in Real-time Analytics(also is memsql,recommended)
- [x] LEO – DB2’s LEarning Optimizer (bad)
- [ ] Apache Calcite: A Foundational Framework for Optimized Query Processing Over Heterogeneous Data Sources
- [ ] The Cascades framework for query optimization

### 1.3 join order (current need read)
- [ ] Improving Join Reorderabilitywith Compensation Operators
- [x] On the Correct and Complete Enumeration of the Core Search Space
- [ ] Dynamic Programming Strikes Back
- [ ] Left Bit Right: For SPARQL Join Queries with OPTIONAL Patterns (Left-outer-joins)
- [x] Flow-Join: Adaptive skew handling for distributed joins over high-speed networks

### 1.4 statistic info & estimation
- [x] How Good Are Query Optimizers, Really?(some expriment,good)
- [x] Modeling skewed distribution using multifractals and the80-20'law(good)
- [x] Cardinality Estimation: An Experimental Survey
- [ ] Two-Level Sampling for Join Size Estimation
- [ ] Lightweight Cardinality Estimation in LSM-based Systems
- [ ] Summarizing and Mining Skewed Data Streams


### 1.5 cost model
- [x] Access Path Selection in Main-Memory Optimized Data Systems: Should I Scan or Should I Probe?(some expriments,good)
- [x] System R: relational approach to database management. ACM Transactions on Database Systems(classsical paper,good)
- [ ] A cost model for the estimation of query execution time in a parallel environment supporting pipeline



## 2.system architecture
- [x] Spanner: Becoming a SQL System (recommended)
- [x] F1: A Distributed SQL Database That Scales (recommended)
- [ ] F1 Query: Declarative Querying at Scale Bart
- [x] Amazon Aurora: Design Considerations for High Throughput Cloud-Native Relational Databases
- [x] PolarFS: An Ultra-low Latency and Failure Resilient Distributed File System for Shared Storage Cloud Database
- [ ] Impala: A Modern, Open-Source SQL Engine for Hadoop
- [ ] Anti-Caching: A New Approach to Database Management System Architecture
- [x] MapReduce: Simplified Data Processing on Large Clusters 
- [x] The Google File System
- [x] Bigtable: A Distributed Storage System for Structured Data
- [ ] Anna: A KVS For Any Scale
- [ ] Eliminating Boundaries in Cloud Storage with Anna
- [x] AnalyticDB: Real-time OLAP database system at Alibaba Cloud
- [ ] Cloud native database systems at Alibaba: Opportunities and challenges
- [ ] Large-scale incremental processing using distributed transactions and notifications
- [ ] Multi-model Databases: A new journey to handle the variety of data
- [x] TiDB: A Raft-based HTAP Database
- [x] Spark SQL: Relational Data Processing in Spark
- [x] Cloud native database systems at Alibaba: Opportunities and challenges
- [ ] Multi-model Databases: A new journey to handle the variety of data



### 2.1 Column-store

- [x] C-store: a column-oriented DBMS
- [x] Column-Stores vs. Row-Stores: How Different Are They Really?
- [x] The Vertica Analytic Database: C-Store 7 Years Later
- [x] Query execution in column-oriented database systems
- [x] Integrating Compression and Execution in Column-Oriented Database Systems 
- [x] Bridging the Archipelago between Row-Stores and Column-Stores for Hybrid Workloads



## 3 transcation

### 3.1 acid & base
- [x] Salt: Combining ACID and BASE in a Distributed Database (good)




## 4 nosql

### 4.1 overview
- [x] Scalable SQL and NoSQL Data Stores



## 5 Execution

### 5.1 MPP

- [ ] Comparative Study Parallel Join Algorithms for MapReduce environment



### 5.2 Concurrency control

- [ ] Franklin, M. (1997). Concurrency control and recovery. The Computer Science and Engineering Handbook, (c), 1058–1077. 
- [ ] Abadi, D. J., & Madden, S. (2008). Query Execution in Column-Oriented Database Systems.



### 5.3 Data Structure

- [ ] Zhang, H., Andersen, D. G., Kaminsky, M., Keeton, K., & Pavlo, A. (n.d.). SuRF : Practical Range Query Filtering with Fast Succinct Tries.



## 6. Data lake

- [x] Delta Lake : High-Performance ACID Table Storage over Cloud Object Stores
- [x] Lakehouse: A New Generation of Open Platforms that Unify Data Warehousing and Advanced Analytics
- [x] [Hudi: Uber Engineering’s Incremental Processing Framework on Apache Hadoop](https://eng.uber.com/hoodie/)
- [x] [slides: Lakehouse Technology as the Future of Data Warehousing](http://web.stanford.edu/class/cs245/slides/LakehouseGuestTalk.pdf)



## 7.I/O

- [ ] Raghavan, D., Levis, P., Zaharia, M., & Zhang, I. (2021). Breakfast of champions: Towards zero-copy serialization with NIC scatter-gather. HotOS 2021 - Proceedings of the 2021 Workshop on Hot Topics in Operating Systems, 199–205. https://doi.org/10.1145/3458336.3465287 [paper](https://cs.stanford.edu/~matei/papers/2021/hotos_serialization.pdf)



## 8. Stream System

- [ ] Johansson, T., & Bergvik, A. (1975). Naiad: A Timely Dataflow System Derek. Acta Neurologica Scandinavica, 52(1), 63–70. https://doi.org/10.1111/j.1600-0404.1975.tb02828.x
- [ ] Gjengset, J., Schwarzkopf, M., Behrens, J., Araújo, L. T., Kohler, E., Kaashoek, M. F., … Morris, R. (2018). Noria: dynamic, partially-stateful data-flow for high-performance web applications.
- [ ] 
