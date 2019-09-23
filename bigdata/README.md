# 大数据

## 什么是大数据

```text
    大数据（BIG DATA），指无法在一定时间范围内用常规软件工具进行捕捉、管理和处理的数据集合，是需要新处理模式才能具有更强的决策力、洞察发现力和流程优化能力的海量、高增长率和多样化的信息资产（百度百科的定义）

    在目前的业界尚未对大数据由清晰明确的定义, 它的第一次出现是在麦肯锡公司的报告中出现的, 在维基百科上的较为模糊的定义是很难运用软件的手段获取大量的内容信息, 对其处理后整理得出的数据集合。其他计算机学科的学者给出的定义是数据的尺度极为巨大, 常规的数据处理软件无法对数据识别、存储和应用的海量数据信息
```

## 数据单位

1MB = 1024KB、1GB = 1024MB

1TB = 1024GB、1PB = 1024TB

## 大数据的特征

容量（Volume）：数据的大小决定所考虑的数据的价值和潜在的信息；

种类（Variety）：数据类型的多样性；

速度（Velocity）：指获得数据的速度；

可变性（Variability）：妨碍了处理和有效地管理数据的过程。

真实性（Veracity）：数据的质量

复杂性（Complexity）：数据量巨大，来源多渠道

价值（value）：合理运用大数据，以低成本创造高价值

## 大数据学习路线

| Technology | Introduction |
| :--- | :--- |


| JAVA | 面向对象的编程语言 |
| :--- | :--- |


| Linux | 类Unix操作系统 |
| :--- | :--- |


| Hadoop生态圈 |  |
| :--- | :--- |


<table>
  <thead>
    <tr>
      <th style="text-align:left">1&#x3001;HDFS</th>
      <th style="text-align:left">
        <p>&#x89E3;&#x51B3;&#x5B58;&#x50A8;&#x95EE;&#x9898;</p>
        <p>&#x5B58;&#x50A8;&#x6781;&#x5927;&#x6570;&#x76EE;&#x7684;&#x4FE1;&#x606F;&#xFF08;terabytes
          or petabytes&#xFF09;&#xFF0C;&#x5C06;&#x6570;&#x636E;&#x4FDD;&#x5B58;&#x5230;&#x5927;&#x91CF;&#x7684;&#x8282;&#x70B9;&#x5F53;&#x4E2D;&#x3002;&#x652F;&#x6301;&#x5F88;&#x5927;&#x5355;&#x4E2A;&#x6587;&#x4EF6;&#x3002;</p>
        <p>&#x63D0;&#x4F9B;&#x9AD8;&#x53EF;&#x9760;&#x6027;&#xFF0C;&#x662F;&#x6307;&#x4E00;&#x4E2A;&#x6216;&#x591A;&#x4E2A;&#x8282;&#x70B9;&#x6545;&#x969C;&#xFF0C;&#x7CFB;&#x7EDF;&#x4ECD;&#x7136;&#x53EF;&#x4EE5;&#x7EE7;&#x7EED;&#x5DE5;&#x4F5C;</p>
        <p>&#x63D0;&#x4F9B;&#x6570;&#x636E;&#x5FEB;&#x901F;&#x8BBF;&#x95EE;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table><table>
  <thead>
    <tr>
      <th style="text-align:left">2&#x3001;MapReduce</th>
      <th style="text-align:left">
        <p>&#x89E3;&#x51B3;&#x8BA1;&#x7B97;&#x95EE;&#x9898;</p>
        <p>&#x5B83;&#x6709;&#x4E2A;&#x7279;&#x70B9;&#x5C31;&#x662F;&#x4E0D;&#x7BA1;&#x591A;&#x5927;&#x7684;&#x6570;&#x636E;&#x53EA;&#x8981;&#x7ED9;&#x5B83;&#x65F6;&#x95F4;&#x5B83;&#x5C31;&#x80FD;&#x628A;&#x6570;&#x636E;&#x8DD1;&#x5B8C;&#xFF0C;&#x4F46;&#x662F;&#x65F6;&#x95F4;&#x53EF;&#x80FD;&#x4E0D;&#x662F;&#x5F88;&#x5FEB;&#x6240;&#x4EE5;&#x5B83;&#x53EB;&#x6570;&#x636E;&#x7684;&#x6279;&#x5904;&#x7406;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>| 3、Yarn | 资源协调者 |
| :--- | :--- |


<table>
  <thead>
    <tr>
      <th style="text-align:left">4&#x3001;ZooKeeper</th>
      <th style="text-align:left">
        <p>&#x5206;&#x5E03;&#x5F0F;&#x5E94;&#x7528;&#x7A0B;&#x5E8F;&#x534F;&#x8C03;&#x670D;&#x52A1;</p>
        <p>&#x4E00;&#x822C;&#x7528;&#x4E8E;&#x5B58;&#x50A8;&#x4E00;&#x4E9B;&#x76F8;&#x4E92;&#x534F;&#x4F5C;&#x7684;&#x4E00;&#x4E9B;&#x4FE1;&#x606F;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>| 5、Flume | 数据采集工具 |
| :--- | :--- |


| 6、HIve | 基于Hadoop的数据仓库工具 |
| :--- | :--- |


| 7、Hbase | 分布式、面向列的开源数据库，与之类似的非结构化数据库还有MongoDB等 |
| :--- | :--- |


| 8、Sqoop | 数据传递工具，如将数据从关系型数据库到入Hive |
| :--- | :--- |


| Scala | 多范式编程语言、面向对象和函数式编程的特性 |
| :--- | :--- |


<table>
  <thead>
    <tr>
      <th style="text-align:left">Spark</th>
      <th style="text-align:left">
        <p>&#x76EE;&#x524D;&#x4F01;&#x4E1A;&#x5E38;&#x7528;&#x7684;&#x6279;&#x5904;&#x7406;&#x79BB;&#x7EBF;&#x6570;&#x636E;/&#x5B9E;&#x65F6;&#x8BA1;&#x7B97;&#x5F15;&#x64CE;</p>
        <p>&#x5B83;&#x662F;&#x7528;&#x6765;&#x5F25;&#x8865;&#x57FA;&#x4E8E;MapReduce&#x5904;&#x7406;&#x6570;&#x636E;&#x901F;&#x5EA6;&#x4E0A;&#x7684;&#x7F3A;&#x70B9;&#xFF0C;&#x5B83;&#x5F88;&#x662F;&#x6D41;&#x6C13;&#xFF0C;&#x76F4;&#x63A5;&#x5C06;&#x6570;&#x636E;&#x5B58;&#x5728;&#x5185;&#x5B58;&#x4E2D;</p>
        <p>&#x3010;&#x6CE8;&#x610F;&#x3011;MapReduce&#x8FD0;&#x884C;&#x65F6;&#x4E5F;&#x662F;&#x9700;&#x8981;&#x5C06;&#x4EE3;&#x7801;&#x6570;&#x636E;&#x52A0;&#x8F7D;&#x5230;&#x5185;&#x5B58;&#x4E2D;&#x7684;&#xFF0C;&#x53EA;&#x4E0D;&#x8FC7;Spark&#x90FD;&#x662F;&#x57FA;&#x4E8E;&#x5185;&#x5B58;&#x64CD;&#x4F5C;</p>
      </th>
    </tr>
  </thead>
  <tbody></tbody>
</table>| Flink | 目前最火的流式处理框架、既支持流处理、也支持批处理 |
| :--- | :--- |


| Elasticsearch | 大数据分布式弹性搜索引擎 |
| :--- | :--- |


起源：Google 在大数据方面的三大论文 （谷歌三宝）

[在github大的当前目录下](https://github.com/lyhcc/NoteBook/tree/master/bigdata)

[三宝的介绍](https://www.cnblogs.com/javhu/archive/2013/03/25/cyue_hadoop_google.html)



## Hadoop 三大发行版本

1. Apache、Cloudera、Hortonworks Apache版本最原始、最基础：适合零基础 大公司在用
2.  Cloudera Cloudera’s DistributionIncluding Apache Hadoop 简称CDH 中小型公司用、简单方便、自带可视化 
3. Hortonworks  文档较好  注：Cloudera 和Hortonworks 在2018年10月，国庆期间宣布合并

## 硬件要求

**内存：  
         最大支持内存查询：**  
         win + R  
         **输入** wmic memphysical get maxcapacity  
         **计算**MaxCapacity/1024/1024GB  
**硬盘：**500G+

