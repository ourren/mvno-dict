# 虚拟运营商170/171号段归属地及品牌查询

全国170/171号段虚拟运营商 归属地 及运营企业 数据索引库

请见 dict_tel_170.php
使用示例: https://www.it68.com.cn/file/tel/

---
### 数据说明
 1. 前三位 `170`/`171` 为号段, 由工信部统一分配, 不同于传统号段, `170`/`171`为三网共享号段,
 一个号段即可能有移动联通也可能有电信.
 2. 第四位 `1700`/`1705`/`1709` 为网络标识位, 如`1700`为电信网段, `1705`为移动网段, `1709`为联
 通网段.
 3. 第五位至第七位 `1700021` 此为品牌标识位, 真正运营的企业需要到第七位才能确定. 如
 '1700021' => ['广东', '小米移动', '电信'], 表示`1700021`开头所有号码均是`小米移动`品牌
 , 归属地为广东, 网络制式为电信.

---
### 数据来源
 1. 各虚拟运营商选号中心枚举
 2. 网上已经存在数据库合并提取
 3. 各位的pull request

 如果您使用了本项目, 并且您手里有更精确的数据, 欢迎提交pull request

 : )

---
### 授权
MIT