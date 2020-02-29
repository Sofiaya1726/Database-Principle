# Database-Principle
关于关系型数据库管理系统的调研结果：

关系型数据库系统通过数据、关系和对数据的约束三者组成的数据模型来存放和管理数据。
业界普遍使用的关系型数据库管理系统产品有: IBM DB2通用数据库、Oracle以及SQL Server等。

1. 在操作系统方面，关系型数据库各有优缺点。
一部分数据库支持全部操作系统，
如Apache Derby2, Firebird, HSQLDB2, H2 2, Ingres, MySQL, OpenLink Virtuoso, SmallSQL, SQLite;
一部分数据库支持部分操作系统，
如PostgreSQL, DB2, Informix等；

2. 在可实现的基本功能方面，各有优缺点。
大多数数据库能够实现ACID关联完整性，数据库事务， Unicode万国码。
如postgreSQL, Apache Derby, Firebird, Informix, MySQL等；

3. 下面简述几种常见关系型数据库系统。
DB2：
          IBM出口的一系列关系型数据库管理系统，分别在不同的操作系统平台上服务。
          虽然DB2产品是基于UNIX的系统和个人计算机操作系统，在基于UNIX系统和微软在windows系统下的Access方面，DB2追寻了ORACLE的数据库产品。
Oracle：
          关系型数据库管理系统，它功能强大、性能卓越，在当今大型数据库管理系统中占有重要地位。
Informix：
　　  IBM公司出品（2001）的关系数据库管理系统（RDBMS）家族。
         作为一个集成解决方案，它被定位为作为IBM在线事务处理（OLTP）旗舰级数据服务系统。
         在1980年成立，目的是为Unix等开放操作系统提供专业的关系型数据库产品。
         Informix第一个真正支持SQL语言的关系数据库产品是Informix SE（StandardEngine）。
         InformixSE是在当时的微机Unix环境下主要的数据库产品。它也是第一个被移植到Linux上的商业数据库产品。
Sybase：
　　  一种典型的UNIX或WindowsNT平台上客户机/服务器环境下的大型数据库系统。
         Sybase提供了一套应用程序编程接口和库，可以与非Sybase数据源及服务器集成，允许在多个数据库之间复制数据，适于创建多层应用。系统具有完备的触发器、存储过程、规则以及完整性定义，支持优化查询，具有较好的数据安全性。
         Sybase通常与SybaseSQLAnywhere用于客户机/服务器环境，前者作为服务器数据库，后者为客户机数据库，采用该公司研制的PowerBuilder为开发工具，在我国大中型系统中具有广泛的应用。
 SQL Server：
　　  SQL Server的功能比较全面，效率高，可以作为中型企业或单位的数据库平台。SQL Server可以与Windows操作系统紧密集成，不论是应用程序开发速度还是系统事务处理运行速度，都能得到较大的提升。
         对于在Windows平台上开发的各种企业级信息管理系统来说，不论是C/S（客户机/服务器）架构还是B/S（浏览器/服务器）架构，SQL Server都是一个很好的选择。
         SQL Server的缺点是只能在Windows系统下运行。   
PostgreSQL：
　　  PostgreSQL 是一种特性非常齐全的自由软件的对象——关系性数据库管理系统（ORDBMS），它的很多特性是当今许多商业数据库的前身。
         PostgreSQL 的特性覆盖了SQL-2/SQL-92和SQL-3。首先，它包括了可以说是目前世界上最丰富的数据类型的支持；
         其次，目前PostgreSQL 是唯一支持事务、子查询、多版本并行控制系统、数据完整性检查等特性的唯一的一种自由软件的数据库管理系统.
MySQL：
　　  目前MySQL被广泛地应用在Internet上的中小型网站中。由于其体积小、速度快、总体拥有成本低，尤其是开放源码这一特点，许多中小型网站为了降低网站总体拥有成本而选择了MySQL作为网站数据库。
Access数据库：
         Access能够存取 Access/Jet、Microsoft SQL Server、Oracle，或者任何 ODBC 兼容数据库的资料。Access界面友好而且易学易用，作为Office套件的一部分，可以与Office集成，实现无缝连接Access提供了表(Table)、查询(Query)、窗体(Form)、报表(Report)、宏(Macro)、模块(Module)等用来建立数据库系统的对象。提供了多种向导、生成器、模板，把数据存储、数据查询、界面设计、报表生成等操作规范化。
　　  Access是入门级小型桌面数据库，性能安全性都很一般。可供个人管理或小型网站之用。

经过以上比较，我们得出结论如下：一般的中小型企业或者中小型的应用中，采用MS SQL Server 作为数据平台，既可以节约资金，又便于维护管理。小型应用主要考虑的是资金问题，SQL Server的资金投入最小，是中小型应用的最佳选择。
大型应用系统要求有较高的数据处理能力，一般应该采用了高性能的大型数据库管理系统——Oracle，大型高可靠性要求的系统安全稳定性是首要考虑的因素，Oracle 能够提供很高的安全稳定的性能，因此Oracle是在国内的大型数据库的必然的选择。
在国外的巨型企业中很多采用全套IBM解决方案，使用DB2作为公司的数据仓库，可以达到几乎与Oracle相同的安全稳定性和相近的性能，但是国内使用DB2的人很少，经验丰富的管理员更少，很难实现很好的数据库管理。
在银行和证券系统中，采用安全性较好的INFORMIX和SYBASE。随着SQL2000的发布和完善，在大型数据库应用中Microsoft也将占一席之地。  


（*以上资料来源于百度百科及网络）
参考网址：
https://www.cnblogs.com/chamie/p/4715546.html
https://baike.baidu.com/item/关系型数据库系统/15540093?fr=aladdin
