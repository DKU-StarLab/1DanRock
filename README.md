# 1DanRock

2025 [DKU System Software Lab](https://sslab.dankook.ac.kr/) RocksDB Study

## Goals
* Share Experiences with Open Source Analysis
* Manage GitHub Repository
* Write a Research Paper (Final Goal)

## Schedule
### Paper Presentation
|         | Date      | Content                                                                               | Presenter                               |
| :------ | :-------- | :------------------------------------------------------------------------------------ | :-------------------------------------- |
| Week 0  | 25-01-08  | ["Kick-off Meeting"](./presentation_file/W0_HojinShin_Kick-off.pdf)                                                                  | Hojin Shin |
| Week 1 | 25-01-14  | ["Introduction 1"](./presentation_file/W1_HojinShin_Introduction1.pdf)| Hojin Shin |


### Evaluation Presentation
|        |          | Presenter                               | Contents |
| :----- | :------- | :-------------------------------------- | :------- |
| Week |  | |  |

### Teams
* Student:
  - 1.Daeeun Lee, Gyeongjun Ha
  - 2.Juhee Park, Hyoeun Chae
  - 3.Suhwan Shin, Zhu Yongjie
  - 4.Dayeon Wi, Seonghyeon Cho
  - 5.Yongmin Lee, Hojin Shin


## Paper & Lecture List
### Paper
- SkipList-based
  - William Pugh, "Skip lists: a probabilistic alternative to balanced trees", Communications of the ACM 1990
  - Zhongle Xie, et al. "Parallelizing Skip Lits for In-Memory Multi-Core Database Systems", ICDE 2017
  - Jeseong Yeon, et al. "JellyFish: A Fast Skip List with MVCC", Middleware '20
  - Tyler Crain, et al. "No Hot Spot Non-blocking Skip List", ICDCS 2013
  - Henry Daly, et al. "NUMASK: High-Performance Scalable Skip List for NUMA", DISC 2018 [:octocat:](https://github.com/sss-lehigh/numask.git)
  - Yedam Na, et al. "ESL: A High-Performance Skiplist with Express Lane", MDPI 2023
  - Zhongle Xie, et al. "PI: a parallel in-memory skip list based index", CoRR 2016
  - Tadeusz Kobus, et al. "Jiffy: a lock-free skip list with batch updates and snapshots", PPoPP '22 [:octocat:](https://github.com/tkobus/jiffy.git)
  - Vitaly Aksenov, et al. "The splay-list: a distribution-adaptive concurrent skip-list", Distributed Computing 2023

- Key-value Separation
  - Dai, Yifan, et al. "From WiscKey to Bourbon: A Learned Index for Log-Structured Merge Trees." FAST 16
  - Chan, Helen HW, et al. "HashKV: Enabling Efficient Updates in KV Storage via Hashing." ATC 18
  - Li, Yongkun, et al. "Differentiated Key-Value storage management for balanced I/O performance." ATC 21
  - Tang, Chenlei, et al. "Fencekv: Enabling efficient range query for key-value separation." IEEE TPDS 22

- Storage/PM(Persistent Memory)-based
  - Kannan, Sudarsun, et al. "Redesigning LSMs for Nonvolatile Memory with NoveLSM." FAST 18
  - Yao, Ting, et al. "MatrixKV: Reducing Write Stalls and Write Amplification in LSM-tree Based KV Stores with Matrix Container in NVM." ATC 20
  - Ding, Chen, et al. "TriangleKV: Reducing write stalls and write amplification in LSM-tree based KV stores with triangle container in NVM."  IEEE TPDS 22
  - Zhang, Wenhui, et al. "ChameleonDB: a key-value store for optane persistent memory." EuroSys 21
  - Fernando, Pradeep, et al. "Blizzard: Adding True Persistence to Main Memory Data Structures." arXiV 23
  - Song, Yongju, et al. "Prism: Optimizing key-value store for modern heterogeneous storage devices." ASPLOS 23
  - Duan, Zhuohui, et al. "Revisiting log-structured merging for kv stores in hybrid memory systems." ASPLOS 23
  - Wang, Jing, et al. "Revisiting Secondary Indexing in LSM-based Storage Systems with Persistent Memory." ATC 23
  - Lepers, Baptiste, et al. "Kvell: the design and implementation of a fast persistent key-value store." SOSP 19
  - Chen, Hao, et al. "SpanDB: A fast,Cost-Effective LSM-tree based KV store on hybrid storage." FAST 21
  - Li, Cheng, et al. "Leveraging NVMe SSDs for building a fast, cost-effective, LSM-tree-based KV store." ACM TOS 21

- Structure/Operation Optimization
  - Wu, Xingbo, et al. "LSM-trie: An LSM-tree-based Ultra-Large Key-Value Store for Small Data Items." ATC 15
  - Dayan, Niv, et al. "Monkey: Optimal navigable key-value store." SIGMOD 17
  - Thonangi, et al. "On log-structured merge for solid-state drives." ICDE 17
  -  Zhan, Ling, et al. "WOKV: A write-optimized key-value store." ICCCBDA 18
  - Dayan, Niv, et al. "Dostoevsky: Better space-time trade-offs for LSM-tree based key-value stores via adaptive removal of superfluous merging." SIGMOD 18
  - Wang, Xiaoliang, et al. "Reducing write amplification of lsm-tree with block-grained compaction." ICDE 22
  - Xu, Peng, et al. "LUDA: boost LSM key value store compactions with gpus." VLDB 20
  - Yang, Lei, et al. "Leaper: A learned prefetcher for cache invalidation in LSM-tree based storage engines." VLDB 20
  - Zhong, Wenshao, et al. "REMIX: Efficient Range Query for LSM-trees." FAST 21
  - Lu, Kai, et al. "TridentKV: A read-optimized LSM-tree based KV store via adaptive indexing and space-efficient partitioning." IEEE TPDS 21
  - Lu, Ziyi, et al. "p2kvs: a portable 2-dimensional parallelizing framework to improve scalability of key-value stores on ssds." EuroSys 22
  - Kim, Wonbae, et al. "ListDB: Union of Write-Ahead logs and persistent SkipLists for incremental checkpointing on persistent memory." OSDI 22
  - Balmau, Oana, et al. "TRIAD: Creating synergies between memory, disk and log in log structured Key-Value stores." ATC 17
  - Balmau, Oana, et al. "SILK: Preventing latency spikes in Log-Structured merge Key-Value stores." ATC 19
  - Yu, Jinghuan, et al. "ADOC: Automatically Harmonizing Dataflow Between Components in Log-StructuredKey-Value Stores for Improved Performance."  FAST 23
  - Dai, Yifan, et al. "From WiscKey to Bourbon: A Learned Index for Log-Structured Merge Trees." OSDI 20
  - Wang, Wenlong, et al. "LearnedKV: Integrating LSM and Learned Index for Superior Performance on SSD." arxiv 24
  - Wang, Yi, et al. "LeaderKV: Improving Read Performance of KV Stores via Learned Index and Decoupled KV Table." ICDE 24

### Lecture
  - [CMU, "Intro to Database Systems", Fall 2023](https://youtube.com/playlist?list=PLSE8ODhjZXjbj8BMuIrRcacnQh20hmY9g&si=vIqTjyEuCJWWfprn)
    - This course is about the design/implementation of DBMS, not about "how to use a DBMS".
    - It is recommended to understand indexes in the overall flow of DBMS. **Be sure to take courses 7, 8, and 9**.
  - [Tim Kraska, "AWS On Air ft. How will AI revolutionize databases?", 2023](https://youtu.be/zyRmXFj_ej4?si=UdfpqIeCJaos0R0W)
  - [Jongmoo Choi,"Key-Value Store: Database for Unstructured Bigdata (KOR)",  2021](https://mooc.dankook.ac.kr/courses/61d537a3b6b71841651153b3) [:bar_chart:](https://github.com/DKU-StarLab/leveldb-study/blob/761b550973ab6d1e88189190e66c0ee19a52aa12/introduction/Jongmoo%20Choi,%20Key-Value%20Store%20-%20Database%20for%20Unstructured%20Bigdata,%202021.pdf)
  - [MIT, "Machine Learning for Systems", 2021](https://dsg.csail.mit.edu/6.887/sched.php)

### For Beginners
  - Lectures
    - [SNU 쓰디연구소, JTJ의 리눅스탐험 (linux, makefile, vim, gdb)](https://youtube.com/playlist?list=PL0vWyY_q7XP_JMzDKVbOc3aXEEDPjYTUX&si=O8SHNAuP1eD8tShn)
    - [따라하면서 배우는 Shell Programming](https://youtube.com/playlist?list=PLApuRlvrZKog2XlvGJQh9KY8ePCvUG7Je&si=kfY4Uw9oPrRjskCo)
    - [Matplotlib 단기집중과정](https://youtu.be/3Xc3CA655Y4?si=7vqUTosyHWppuADv)
    - [제대로 파는 Git & GitHub - 깃 끝.장.내.기](https://youtu.be/1I3hMwQU6GU?si=fW8B-39g8SR4X_Sv)
  
  - Documents
    - [권창현, "박사과정 학생이 유의해야 하는 점"](https://thoughts.chkwon.net/phd-student-professor-faq/)
    - [문수복, "개별연구/졸업연구를 고민하는 학생들을 위한 간추린 자료"](https://sbmoon.tistory.com/245)
    - [문수복, "논문 제 1 저자의 책임"](https://sbmoon.tistory.com/253)  
    - [S. Keshav, "How to Read a Paper"](https://web.stanford.edu/class/ee384m/Handouts/HowtoReadPaper.pdf)
    - [Remzi Arpaci-Dusseau, "Graduate School: Keys To Success"](https://youtu.be/fqPSnjewkuA?si=adHJlDhKV06bmdrH)
    - [Remzi Arpaci-Dusseau, "25 Years of Storage Research and Education: A Retrospective"](https://youtu.be/u9RECEzxk6I?si=yA7FVDKOD0RzVlGi)

* Tools
  - [GDB](https://www.sourceware.org/gdb/)
  - [Understand](https://licensing.scitools.com/download) 
  - [Uftrace](https://github.com/namhyung/uftrace)

* File
  - [presentation file format](./presentation_file/presentation_file_format.pptx)
  - [kcc research paper format](./file/%5Bformat%5Dresearch_paper(KCC).hwp)

* Previous Study
  - [DKU Leveldb Study, 2022](https://github.com/DKU-StarLab/leveldb-study)
  - [DKU RocksDB Festival, 2021](https://github.com/DKU-StarLab/RocksDB_Festival)

## Members
* Student: [Suhwan Shin](https://github.com/Student5421), [Zhu Yongjie](https://github.com/arashio1111), Daeeun Lee, Juhee Park, Yongmin Lee, Dayeon Wi, Seonghyeon Cho, Hyoeun Chae, Gyeongjun Ha
* Assistant: [Hojin Shin](https://github.com/shinhojin), [Guangxun Zhao](https://github.com/ErosBryant)
* Professor: [Jongmoo Choi](http://embedded.dankook.ac.kr/~choijm/)

## Schedule
* Date: Every Tuesday in January, February
* Time: 14:00 ~ 16:00
* Place: Dankook University Software ICT Hall Room 304