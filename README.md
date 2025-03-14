# 引用
本词表来自BCC语料库汉语部分的报刊（news）、科技（technology）、博客（blog）、微博（weibo）和文学（literature）几个频道。Global为此五个频道合并后的全局词表。

词表剪枝频次为10。未去除字母词。存在部分数量词残留。

本词表仅供学术使用。引用请注明“北京语言大学BCC语料库http://bcc.blcu.edu.cn”和文献（以bcc网站的最新引用说明为准）。最终解释权归北语大数据与教育技术研究所所有。


北京语言大学·信息科学学院·大数据与教育技术研究所
2015年10月

联系人：荀恩东，edxun@126.com

# 概述
最近大模型兴起，基于中文文字、字体、图片相关的中文模型较少，训练中文模型需要，现开发相关中文文字、字体、图片中文的基础工具，开源给大家使用，欢迎大家star，谢谢。


# 随机生成中文字符
本工具包根据BCC语料库汉语词表词频获取中文字符，随机生成的，已标明数据来源，如有侵权，请通知下线谢谢。

## 使用方法

### 安装
```commandline
pip install chineserand
```

### 1.生成随机文字
```python
from chineserand import raw
chinese_words = raw(10)
print(chinese_words) 
```

### 2.生成句子
```python
from chineserand import sentences
many_sentences = sentences(many=4)
print(many_sentences)
```

如果有任何问题，欢迎提issue。
github地址：
![chineserand](https://github.com/chenzuoli/chineserand)

# 后期规划

1. 随机生成中文词语、语句、段落；
2. 根据操作系统字符集，生成所有中文字体对应的图片（用于字体模型训练）；


------

本项目由【<b>乐知付加密平台</b>】开源，乐知付加密平台，是一个以用户为中心的内容变现平台，无论是专业创作者还是个人爱好者，都可以通过我们平台实现变现梦想。

您无需亲自搭建知识付费服务平台，将知识资源放在网盘中，通过加密平台，进行压缩包密码管理，买家支付后展示网盘中压缩包密码，轻松资源变现。


官网地址：[www.lezhifu.cc](https://lezhifu.cc)

公众号【乐知付加密平台】：
<div style="text-align: center;">  
    <img src="images/image.png" alt="乐知付" style="width: 50%;">  
    <img src="https://img2024.cnblogs.com/blog/1455070/202409/1455070-20240919212128860-1944218544.png" alt="乐知付" style="width: 50%;">  
</div>