# 第 4 章 处理非关系型数据

本章内容：

* 将数据持久化到 Cassandra
* Cassandra 中的数据建模
* 在 MongoDB 中使用文档数据

丰富多彩的生活才乐趣横生。

您可能有最喜欢冰淇淋的味道。您最喜欢的某种口味，通常是因为这比其他更能满足您的欲望。但是大多数人，尽管有自己喜欢的口味，还会不时尝试其他不同的口味。

数据库就像冰淇淋。几十年来，关系型数据库一直是用户最喜欢的类型。但是现在比以往任何时候都有更多的选择。所谓的“NoSQL”数据库提供了不同的概念和结构。尽管选择可能仍然在某种程度上取决于您的喜爱好，但有些数据库更适合于保存其他类型的数据。

幸运的是，Spring Data 支持了许多 NoSQL 数据库，包括 MongoDB、Cassandra、Couchbase、Neo4j、Redis 等等。而且幸运的是，
无论选择哪个数据库，编程模型几乎是相同的。

本章没有足够的篇幅涵盖 Spring Data 支持的所有数据库类型。但为了让您了解 Spring Data 的其他“风味”，我们将研究两种流行的 NoSQL 数据库，Cassandra 和 MongoDB，并了解如何创建 Repository 进行数据持久化。让我们先看看如何使用 Spring Data 创建Cassandra Repository。


