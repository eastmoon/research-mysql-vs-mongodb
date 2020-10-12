# MySQL v.s MongoDB

## MongoDB

+ When to use MongoDB?
    - When you need high availability of data with automatic, fast and instant data recovery.
    - In future, if you’re going to grow big as MongoDB has in-built sharding solution.
    - If you have an unstable schema and you want to reduce your schema migration cost.
    - If you don’t have a Database Administrator (but you’ll have to hire one if you’re going to go BIG).
    - If most of your services are cloud-based, MongoDB is best suitable for you, as its native scale-out architecture enabled by ‘sharding’ aligns well with horizontal scaling and agility offered by cloud computing.

+ MongoDB: Pros & Cons
    - MongoDB is best when you want the flexibility of schema. You can easily use replica sets with MongoDB and can take advantage of scalability. Expansion plans are flexible and can be easily achieved by adding more machines and RAM to the system. It also includes document validations and integrated systems.
    - The cons of MongoDB include higher data size over the period of time. Due to the lack of atomic transactions, the speed is comparatively low compared to NoSQL. Also, the solution is quite infant and hence cannot replace the legacy systems directly.

## MySQL

+ When to use MySQL?
    - If you’re just starting and your database is not going to scale much, MySQL will help you in easy and low-maintenance setup.
    - If you’ve fixed schema and a data structure aren’t going to change over the time like Wikipedia.
    - If you want high performance on a limited budget.
    - If high transaction rate is going to be your requirement (like BBC around 30,000 inserts/minute, 4000 selects/hour)
    - If data security is your top priority, MySQL is the most secure DBMS.

+ MySQL: Pros & Cons
    - MySQL is around the block for a long time. One of the main pros is that it’s community driven. Being a mature solution, it supports JOIN, atomic transactions with privilege and password security system.
    - With MySQL, you may end devoting a lot of time and efforts which other platforms might do automatically for you, like incremental backups. The main issue with MySQL is scalability. No inbuilt XML and OLAP.

## Reference

### Website

#### Database compare

+ [MongoDB vs MySQL: A Comparative Study on Databases](https://www.simform.com/mongodb-vs-mysql-databases/)
+ [Leveraging Elasticsearch for a 1,000% performance boost](https://www.elastic.co/blog/leveraging-elasticsearch-for-a-1000-percent-performance-boost)
+ [MongoDB vs. MySQL](https://dzone.com/articles/comparing-mongodb-amp-mysql)
+ [2019 Database Trends – SQL vs. NoSQL, Top Databases, Single vs. Multiple Database Use](https://scalegrid.io/blog/2019-database-trends-sql-vs-nosql-top-databases-single-vs-multiple-database-use/)
+ [在 NoSQL 和傳統關聯式資料庫之間做出決定](https://navicat.com/cht/company/aboutus/blog/1002-deciding-between-nosql-and-traditional-relational-databases.html)
+ [DB的分類 OLTP與OLAP的區別和介紹 (SQL VS NOSQL) (MYSQL，HBASE如何選擇​)](http://jashliao.eu/wordpress/2019/07/19/db%e7%9a%84%e5%88%86%e9%a1%9e-oltp%e8%88%87olap%e7%9a%84%e5%8d%80%e5%88%a5%e5%92%8c%e4%bb%8b%e7%b4%b9-sql-vs-nosql-mysql%ef%bc%8chbase%e5%a6%82%e4%bd%95%e9%81%b8%e6%93%87%e2%80%8b/)

#### Database theory

+ NoSQL
    - [CAP定理101—分散式系統，有一好沒兩好](https://medium.com/%E5%BE%8C%E7%AB%AF%E6%96%B0%E6%89%8B%E6%9D%91/cap%E5%AE%9A%E7%90%86101-3fdd10e0b9a)
    - [MongoDB 學習筆記之一 - 從 NoSQL 談起](http://garyliutw.blogspot.com/2014/05/mongodb-nosql.html)
+ RMDBS
    - [ACID 特性 wiki](https://zh.wikipedia.org/wiki/ACID)
    - [MySQL 基本運作介紹，從資料庫交易與 ACID 特性開始](https://tw.alphacamp.co/blog/mysql-intro-acid-in-databases)

### PDF

+ [A comparative study: MongoDB vs. MySQL](./pdf/ComparativeStudy-MongoDBvsMSSQL.pdf)
+ [Performance evaluation of SQL and MongoDB databases for big e-commerce data](./pdf/CSSE2015submission85-V2d.pdf)
+ [Database Meets AI: A Survey](./pdf/Database Meets Artificial Intelligence A Survey.pdf)
+ [Performance analysis of NoSQL and relational databases with MongoDB and MySQL](./pdf/Performance analysis of NoSQL and relational databases with.pdf)
+ [SQL vs NoSQL: A Performance Comparison](./pdf/SQL vs NoSQL -  A Performance Comparison.pdf)

# AI Database

## Reference

+ [AI Search Algorithms Every Data Scientist Should Know](https://towardsdatascience.com/ed0968a43a7a)
+ [Artificial Intelligence database: explained](https://blog.datumize.com/artificial-intelligence-database-explained)
+ [AI Databases: What They Are and Why Your Business Should Care](https://www.pcmag.com/news/ai-databases-what-they-are-and-why-your-business-should-care)

# 研究程式

+ 使用 Dokcer 建構與重置資料庫
+ 動態產生指定數量的預設資料
+ 透過標準指令查詢、新增、更新資料
    - 記錄每個指令的時間差
    - 指令會交錯發送，並存在相同指令
+ 實驗分表查詢
