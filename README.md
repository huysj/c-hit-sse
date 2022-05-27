# 重庆邮电大学c语言网站刷题脚本hit sse
## 原理就是打表
### 正常登录然后在脚本文件中更改auth_id（在url中）和NET_SessionId（在cookie中），题目开启后输入题目sessionid即可开始刷题，默认刷到十分以上就算通过，然后可以刷下一题，建议先挂一段时间再刷，避免被发现，计划下周加入一些垃圾代码以免被检测。
### 2022-5-27更新：
**1.解决了input获取的字符串中最后一个字母为'e'时会被忽略的问题。**

**2.解决了部分题目满分超过10分时提前结束答题的问题**

**3.加入了95行垃圾代码，默认关闭，可以在脚本中（约156行）修改注释以开启。***

### 已知问题

**1.题目中带有<或者%的将无法正确处理。（url编码的问题）**

**2.题目输入或者输出过大将无法解决**

**3.当两此输入的个数不一致时无法正确答题（如第一个测试用例输入两个数据而第二个测试用例需要输入三个数据）**
