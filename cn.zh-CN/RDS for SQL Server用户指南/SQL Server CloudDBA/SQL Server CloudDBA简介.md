# SQL Server CloudDBA简介 {#concept_n4q_wnk_xfb .concept}

SQL Server CloudDBA是帮助用户在使用RDS for SQL Server过程中发现问题、诊断问题和智能优化的管理与维护类产品。

## 功能介绍 {#section_mgy_3pk_xfb .section}

SQL Server CloudDBA主要包含如下功能：

-   空间管理：提供分层的监控与分析，从实例深入到数据库，再从数据库深入到表，帮助用户发现和定位数据库空间相关问题，由如下几个部分组成。
    -   空间总览：整体查看空间情况，包括一周变化量、剩余可用空间、已使用空间、预计增长。
    -   空间数据图表信息：以图表形式展示实例的空间使用情况，包括空间使用率、数据日志比、TOP 5数据库空间占用。
    -   空间变化趋势：以图表形式展示实例空间变化情况。
    -   TOP 10数据库：以表格形式展示空间占用TOP 10的数据库详细信息。
    -   TOP 20数据库：以表格形式展示空间占用TOP 20的数据库详细信息。

        ![空间管理](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/64921/154529620132882_zh-CN.png)

-   性能优化：展示数据库的各类关键信息，由如下几个部分组成。
    -   索引缺失：以图表形式展示实例缺失索引的信息以及提供创建缺失索引的语句。
    -   索引使用率：以图表形式展示实例使用索引的详细信息以及提供索引的创建语句。
    -   统计信息：以图表形式展示实例的统计信息详情。
    -   TOP SQL：以图表形式从多个维度对SQL语句进行排序展示，可以查询实时的和历史的TOP SQL。
    -   TOP Objects：实时获取用户实例中对象级别（包括存储过程、函数、触发器等）的性能消耗，帮助用户发现TOP性能消耗的对象以及对象中的SQL语句。

        ![性能优化](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/75752/154529620134754_zh-CN.png)


