# 商品搜索平台后端代码 #

请每次更新根据更新内容填写README.md，以作为版本控制

## 当前功能 ##

1. 初始化商户图 
2. 创建商户，将商户加入商户图
3. 初始化产品图，加入商户中
4. 创建产品，加入产品图
5. 更新商户中的产品图
6. 更新商户图中的商户
7. 由商户图创建倒排索引
8. 线性查找倒排索引
9. 商户及其商品信息存储与读取
10. 倒排索引按时间更新
11. 单/多标签精确搜索、多标签模糊搜索

## 未完成功能 ##

按优先级排序

1. 优先队列关联度搜索
2. 用户相关功能（测试）
3. 功能测试/模块化测试/性能优化
4. 图形界面设计
5. *与服务器端通信功能*

更新时间：2019-05-14

## 更新日志 ##

----

创建时间：2019-04-23

创建内容：自顶而下的存储结构，基本数据结构的构建

创建人：Wh1isper

----

### 更新1 ###

时间：2019-04-23

更新内容：倒排索引的构建

负责人：Wh1isper

----

### 更新2 ###

时间：2019-04-27

更新内容：倒排索引线性查找

负责人：Wh1isper

----

### 更新3 ###

时间：2019-04-29

更新内容：商户及其商品的存储与读取

负责人：Wh1isper

----

### 更新4 ###

时间：2019-04-30

更新内容：

1. 动态表的收缩和测试代码构建
2. 进行了部分测试，修复了一些bug

负责人：Wh1isper

----
### 更新5 ###

时间：2019-05-01

更新内容：

1. 商户操作api构建
2. 进行了部分测试，修复了一些bug
3. 优化了database中的数据传输结构，增加性能
4. main函数下添加了示例代码

负责人：Wh1isper

祝大家五一快乐！

----
### 更新6 ###

时间：2019-05-02

更新内容：

1. 添加了搜索操作实例
2. 创建了模拟数据生成脚本
3. 性能测试以及bug修复

负责人：Wh1isper

----
### 更新7 ###

时间：2019-05-07

更新内容：

1. 多标签精确查找与模糊查找

负责人：Wh1isper

----
### 更新8 ###

时间：2019-05-14

更新内容：

1. 用户功能更新（未测试）
2. 代码注释更新
3. 用户图api更新
4. bug修复
    - 修复了Labellist::append()在执行多个标签同时添加时产生重复的问题
    - 修复了Label2Com::initialTable()在表内有元素时无法初始化的问题
       
负责人：Wh1isper