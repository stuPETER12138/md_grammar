# 我的markdown学习（1/n）

在markdown中引用语言部分。

## 小标题1

`tab`的用法

例如：

<tabs>
<tab title="python1">

```
import pandas
a = pandas.read_excel('xxx'.xlsx)
```

</tab>
<tab title="python2">

```
import numpy

```

</tab>
<tab title="markdown">

```
<tab title="xxx">
</tab>
```
</tab>
</tabs>

## 小标题2

`deflist`的用法

引用别的文章（同一文件夹之下）

<deflist>
    <def title="引用1">
        <include from="Default-topic.md" element-id="add-new-topics"></include>
    </def>
</deflist>

## 小标题3

