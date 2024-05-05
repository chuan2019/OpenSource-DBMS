# OpenSource RDBMS

|         RDBMS        |       Language       |      Column or Row   |     Cloud Native     |                 Github Repo              |                    Affliated Organization                    |
| -------------------- | -------------------- | -------------------- | -------------------- | ---------------------------------------- | ------------------------------------------------------------ |
|     Clickhouse       |         C++          |        Column        |         No           | https://github.com/ClickHouse/ClickHouse | https://www.clickhouse.com                                   |
|    Greenplum DB      |        C/C++         |         Row          |         No           | https://github.com/greenplum-db/gpdb     | https://docs.vmware.com/en/VMware-Greenplum/index.html       |
|      C-Store         |         C++          |        Column        |         No           | https://github.com/eyalroz/c-store       | https://www.vertica.com/                                     |
|     MonetDB          |          C           |        Column        |         No           | https://github.com/MonetDB/MonetDB       | https://www.monetdbsolutions.com/                            |
|       MySQL          |        C++/C         |         Row          |         No           | https://github.com/mysql/mysql-server    | https://dev.mysql.com/                                       |
|      MariaDB         |        C++/C         |         Row          |         No           | https://github.com/MariaDB/server        | https://mariadb.com/                                         |
|     PostgreSQL       |          C           |         Row          |         No           | https://github.com/postgres/postgres     | https://www.postgresql.org/                                  |
|     YugabyteDB       |        C/C++         |        Column        |        Yes           | https://github.com/yugabyte/yugabyte-db  | https://www.yugabyte.com/                                    |
|    FirebirdSQL       |        C++/C         |         Row          |         No           | https://github.com/FirebirdSQL/firebird  | https://firebirdsql.org/                                     |
|    CockroachDB       |         Go           |        Column        |        Yes           | https://github.com/cockroachdb/cockroach | https://www.cockroachlabs.com/product/                       |
|        TiDB          |         Go           |        Column        |        Yes           | https://github.com/pingcap/tidb          | https://www.pingcap.com/                                     |


# OpenSource NoSQL DBMS

|         DBMS         |       Language       |     Cloud Native     |                 Github Repo                   |                    Affliated Organization                    |
| -------------------- | -------------------- | -------------------- | --------------------------------------------- | ------------------------------------------------------------ |
|       ScyllaDB       |         C++          |         Yes          | https://github.com/scylladb/scylladb          | https://www.scylladb.com                                     |
|       MongoDB        |         C++          |         Yes          | https://github.com/mongodb/mongo              | https://www.mongodb.com                                      |
|      Cassandra       |        Java          |         Yes          | https://github.com/apache/cassandra           | https://www.datastax.com/                                    |
|        Redis         |          C           |         Yes          | https://github.com/redis/redis                | https://redis.io/                                            |
|      OrientDB        |        Java          |         Yes          | https://github.com/orientechnologies/orientdb | https://orientdb.org/                                        |

# Important Research Papers and Github Repos

Mohamed A.S, Lyublena A, Venkatesh R, Amr E-H, Zhongxian G, etc. (2014) [Orca: a modular query optimizer architecture for big data](https://dl.acm.org/doi/10.1145/2588555.2595637) SIGMOD '14: Proceedings of the 2014 ACM SIGMOD International Conference on Management of Data, June 2014, pp. 337-348, [PDF](https://15721.courses.cs.cmu.edu/spring2016/papers/p337-soliman.pdf)
 - [GPORCA: the Greenplum Next Generation Query Optimizer](https://github.com/greenplum-db/gporca)

Mario A.M, Yuan S, Michael K and Saman K.H (2015) [ALgorithm selection for black-box continuous optimization problems: a survey on methods and challenges](https://www.sciencedirect.com/science/article/abs/pii/S0020025515003680) Information Sciences, Vol. 317(1), pp. 224-245, [PDF](https://rest.neptune-prod.its.unimelb.edu.au/server/api/core/bitstreams/8ce7ee4d-96c8-5874-9fb0-10f39a1bd2bf/content)

Viktor L, Andrey G, Atanas M, Peter B, Alfons K and Thomas N (2015) [How good are query optimizers, really?](https://dl.acm.org/doi/10.14778/2850583.2850594) Proceedings of the VLDB Endowment, Vol. 9(3), pp. 204-215, [PDF](https://www.vldb.org/pvldb/vol9/p204-leis.pdf)
 - [IMDB/JOB Workload](https://github.com/RyanMarcus/imdb_pg_dataset)

Ryan M, Parimarjan N, Hongzi M, Nesime T, Mohammad A and Time K (2021) [Bao: making learned query optimization practical](https://dl.acm.org/doi/10.1145/3448016.3452838) SIGMOD '21: Proceedings of the 2021 International Conference on Management of Data, June 2021, pp. 1275-1288, [PDF](https://people.csail.mit.edu/tatbul/publications/bao_sigrec22.pdf), [Slides](https://15799.courses.cs.cmu.edu/spring2022/slides/17-queryopt1.pdf)
 - [Bao, a learned query optimizer for PostgreSQL](https://github.com/learnedsystems/BaoForPostgreSQL)
 - [Applying Bao to distributed systems](https://rmarcus.info/blog/2021/06/17/bao-distributed.html)
 - [Ten years of improvements in PostgreSQL's optimizer](https://rmarcus.info/blog/2024/04/12/pg-over-time.html)
 - [Most influential database papers](https://rmarcus.info/blog/2023/07/25/papers.html)

Christoph A, Nesime T, David C, Zhenggang X and Prithviraj P (2023) [AutoSteer: learned query optimization for any SQL database](https://dl.acm.org/doi/10.14778/3611540.3611544) Proceedings of the VLDB Endowment, Vol. 16(12), pp. 3515-3527, [PDF](https://www.vldb.org/pvldb/vol16/p3515-anneser.pdf)
 - [Auto-Steer](https://github.com/IntelLabs/Auto-Steer)
 - [QO-Insight](https://github.com/christophanneser/QO-Insight)

Rong Z, Lianggui W, Wenqing W, Di W, Jiazheng P, Yifan W, etc. (2024) [PilotScope: steering databases with machine learning drivers](https://dl.acm.org/doi/10.14778/3641204.3641209) Proceedings of the VLDB Endowment, Vol 17(5), pp. 980-993 [PDF](https://bolinding.github.io/papers/vldb24pilotscope.pdf)
