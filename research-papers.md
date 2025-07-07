# Important Research Papers and Github Repos

## General Query Optimization Related

Mohamed A.S, Lyublena A, Venkatesh R, Amr E-H, Zhongxian G, etc. (2014) [Orca: a modular query optimizer architecture for big data](https://dl.acm.org/doi/10.1145/2588555.2595637) SIGMOD '14: Proceedings of the 2014 ACM SIGMOD International Conference on Management of Data, June 2014, pp. 337-348, [PDF](https://15721.courses.cs.cmu.edu/spring2016/papers/p337-soliman.pdf)
 - [GPORCA: the Greenplum Next Generation Query Optimizer](https://github.com/greenplum-db/gporca)

Mario A.M, Yuan S, Michael K and Saman K.H (2015) [ALgorithm selection for black-box continuous optimization problems: a survey on methods and challenges](https://www.sciencedirect.com/science/article/abs/pii/S0020025515003680) Information Sciences, Vol. 317(1), pp. 224-245, [PDF](https://rest.neptune-prod.its.unimelb.edu.au/server/api/core/bitstreams/8ce7ee4d-96c8-5874-9fb0-10f39a1bd2bf/content)

Viktor L, Andrey G, Atanas M, Peter B, Alfons K and Thomas N (2015) [How good are query optimizers, really?](https://dl.acm.org/doi/10.14778/2850583.2850594) Proceedings of the VLDB Endowment, Vol. 9(3), pp. 204-215, [PDF](https://www.vldb.org/pvldb/vol9/p204-leis.pdf)
 - [IMDB/JOB Workload](https://github.com/RyanMarcus/imdb_pg_dataset)


## Learned Query Optimizer (LQO)

### Neo

Ryan M, Parimarjan N, Hongzi M, Chi Z, Mohammad A, Tim K, Olga P and Nesime T (2019) [Neo: a learned query optimizer](https://dl.acm.org/doi/10.14778/3342263.3342644) Proceedings of the VLDB Endowment, Vol 12(11), pp. 1705-1718 [PDF](https://www.vldb.org/pvldb/vol12/p1705-marcus.pdf)

### Bao

Ryan M, Parimarjan N, Hongzi M, Nesime T, Mohammad A and Time K (2021) [Bao: making learned query optimization practical](https://dl.acm.org/doi/10.1145/3448016.3452838) SIGMOD '21: Proceedings of the 2021 International Conference on Management of Data, June 2021, pp. 1275-1288, [PDF](https://people.csail.mit.edu/tatbul/publications/bao_sigrec22.pdf), [Slides](https://15799.courses.cs.cmu.edu/spring2022/slides/17-queryopt1.pdf)
 - [Bao, a learned query optimizer for PostgreSQL](https://github.com/learnedsystems/BaoForPostgreSQL)
 - [Applying Bao to distributed systems](https://rmarcus.info/blog/2021/06/17/bao-distributed.html)
 - [Ten years of improvements in PostgreSQL's optimizer](https://rmarcus.info/blog/2024/04/12/pg-over-time.html)
 - [Most influential database papers](https://rmarcus.info/blog/2023/07/25/papers.html)

### Balsa

Zongheng Y, Wei-Lin C, Sifei L, Gautam M, Michael L and Ion S (2022) [Balsa: learning a query optimizer without expert demonstrations](https://dl.acm.org/doi/10.1145/3514221.3517885) SIGMOD '22: Proceedings of the 2022 International Conference on Management of Data, June 2022, pp. 931-944 [PDF](https://dl.acm.org/doi/pdf/10.1145/3514221.3517885)

### Lero

Rong Z, Wei C, Bolin D, Xingguang C, Andreas P, Ziniu W and Jingren Z (2023) [Lero: a learning-to-rank query optimizer](https://dl.acm.org/doi/10.14778/3583140.3583160) Proceedings of the VLDB Endowment, Vol. 16(6), pp. 1466-1479 [PDF](https://www.vldb.org/pvldb/vol16/p1466-zhu.pdf)

### LEON

Xu C, Haitian C, Zibo L, Shuncheng L, Jinghong W, Kai Z, Han S and Kai Z (2023) [LEON: a new framework for ML-aided query optimization](https://dl.acm.org/doi/10.14778/3598581.3598597) Proceedings of the VLDB Endowment, Vol. 16(9), pp. 2261-2273 [PDF](https://www.vldb.org/pvldb/vol16/p2261-chen.pdf)

### LOGER

Tianyi C, Jun G, Hedui C and Yaofeng T (2023) [Loger: a learned optimizer towards generating efficient and robust query execution plans](https://dl.acm.org/doi/abs/10.14778/3587136.3587150) Proceedings of the VLDB Endowment, Vol. 16(7), pp. 1777-1789 [PDF](https://www.vldb.org/pvldb/vol16/p1777-gao.pdf)

### HybridQO

Xiang Y, Chengliang C, Guoliang L and Jiabin L (2022) [Cost-based or learning-based?: a hybrid query optimizer for query plan selection](https://dl.acm.org/doi/abs/10.14778/3565838.3565846) Proceedings of the VLDB Endowment, Vol. 15(13), pp. 3924-3936 [PDF](https://www.vldb.org/pvldb/vol15/p3924-li.pdf)

### AutoSteer

Christoph A, Nesime T, David C, Zhenggang X and Prithviraj P (2023) [AutoSteer: learned query optimization for any SQL database](https://dl.acm.org/doi/10.14778/3611540.3611544) Proceedings of the VLDB Endowment, Vol. 16(12), pp. 3515-3527, [PDF](https://www.vldb.org/pvldb/vol16/p3515-anneser.pdf)
 - [Auto-Steer](https://github.com/IntelLabs/Auto-Steer)
 - [QO-Insight](https://github.com/christophanneser/QO-Insight)

### PilotScope

Rong Z, Lianggui W, Wenqing W, Di W, Jiazheng P, Yifan W, etc. (2024) [PilotScope: steering databases with machine learning drivers](https://dl.acm.org/doi/10.14778/3641204.3641209) Proceedings of the VLDB Endowment, Vol 17(5), pp. 980-993 [PDF](https://bolinding.github.io/papers/vldb24pilotscope.pdf)

### Review

Claude L, Pavel S and Kurt S (2023) [Is your learned query optimizer behaving as you expected? a machine learning perspective](https://dblp.org/rec/journals/corr/abs-2309-01551.html) PVLDB, Vol. 17, 2023-2024, [PDF](https://arxiv.org/pdf/2309.01551)

Guy Lohman (2014) [Is query optimization a "solved" problem?](https://www.semanticscholar.org/paper/Is-query-optimization-a-'solved'-problem-Lohman/c658d835adcda0466052d14f8b81c52c8ee0dd4b) ACM Sigmod Blog [PDF](https://dsf.berkeley.edu/cs286/papers/queryopt-sigmodblog2014.pdf)

## Bandit Algorithm Related

Olivier C and Lihong L (2011) [An empirical evaluation of thompson sampling](https://dl.acm.org/doi/10.5555/2986459.2986710) NIPS'11: Proceedings of the 24th International Conference on Neural Information Processing Systems, Dec. 2011, pp. 2249-2257 [PDF](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/thompson.pdf)



# Database Related Paper Lists on Github

### [Database Learning](https://github.com/pingcap/awesome-database-learning)
### [OLTP](https://github.com/wengsy150943/Paper4OLTPandConcurrencyTesting)
### [OLAP](https://github.com/Wind-Gone/awesome-olap-paper)
### [AI4DB](https://github.com/Wind-Gone/awesome-ai4db-paper)
### [Fuzzing](https://wcventure.github.io/FuzzingPaper/)
### [Industry](https://github.com/Wind-Gone/awesome-dbgiant-Industry-paper)
### [Readings in Database Systems](http://www.redbook.io/all-readings.html)

