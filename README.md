# MybatisForC#SE
本程序为C# 代码库，用法与mybatis接近，不存在编写xml自定义语句，减少编程难度。
## MybatisForC#SE.QueryWrapper
QueryWrapper为代码库提供的语句代写工具类通过调用公共属性CMD{get;}
### public void eq(string column,string value)等等类
命名与mybatis相同且作用一致
## MybatisForC#SE.DateBase
包含数据库连接和基础（增删改查）操作，不可跨表查询。如果需要跨表查询可使用DataBase类公共属性Sqlsever，Sqlsever为SqlConnection类，可使用其进行对语言的自定义。

