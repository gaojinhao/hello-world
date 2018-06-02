# 读写JSON数据
## 问题
  你想读写JSON(JavaScript Object Notation)编码格式的数据。
## 解决方案
  `json`模块提供了一种很简单的方式来编码和解码JSON数据。 其中两个主要的函数是 `json.dumps()` 和 `json.loads()` ， 要比其他序列化函数库如pickle的接口少得多。 下面演示如何将一个Python数据结构转换为JSON：
  ```Python
  import json

  data = {
    'name' : 'ACME',
    'shares' : 100,
    'price' : 542.23
      }

  json_str = json.dumps(data)
  ```
  [妹子图](http://www.meizitu.com/)
  ![MM](http://mm.chinasareview.com/wp-content/uploads/2017a/08/02/08.jpg)
  >数据结构
  >>树
  >>>二叉树
  >>>>平衡二叉树
