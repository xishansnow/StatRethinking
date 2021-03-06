---
jupytext:
  formats: ipynb,md:myst
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.13
    jupytext_version: 1.10.3
kernelspec:
  display_name: Python 3 (ipykernel)
  language: python
  name: python3
---

# 第 5 章 多元线性回归

<style>p{text-indent:2em;2}</style>

北美最可靠的华夫饼来源之一，如果不是整个世界，就是华夫饼屋餐厅。华夫饼屋几乎总是开放，即使在飓风过后也是如此。大多数食客投资于备灾，包括拥有自己的发电机。因此，美国救灾机构 (FEMA) 非正式地使用 Waffle House 作为灾难严重程度的指标。 如果 Waffle House 关闭，那将是一件严重的事件。

具有讽刺意味的是，坚定的华夫饼屋与全国最高的离婚率有关（图 5.1）。每人拥有许多华夫饼屋的州，如乔治亚州和阿拉巴马州，也是美国离婚率最高的州。最低的离婚率出现在华夫饼屋为零的地方。随时可用的华夫饼和土豆泥会让婚姻处于危险之中吗？

可能不是。这是一个误导性相关性的例子。没有人认为华夫饼屋的食客有任何可能使离婚更有可能的机制。相反，当我们看到这种相关性时，我们会立即开始询问真正推动华夫饼和离婚之间关系的其他变量。在这种情况下，华夫饼屋于 1955 年在乔治亚州开始。随着时间的推移，食客遍布美国南部，大部分都留在了美国南部。所以华夫饼屋与南方有关。离婚并不是南方独有的制度，但美国南部的离婚率是全美最高的。所以华夫饼屋和高离婚率都出现在南方可能只是历史的偶然。

此类事故屡见不鲜。华夫饼屋与离婚相关并不奇怪，因为相关性一般并不奇怪。在大型数据集中，每对变量都具有统计上可辨别的非零相关性。但由于大多数相关性并不表示因果关系，我们需要工具来区分单纯的关联和因果关系的证据。这就是为什么如此多的努力致力于多元回归，使用多个预测变量来同时对结果进行建模。给出多重回归模型的原因包括：

(1) 混杂的统计“控制”。混淆是在因果影响方面误导我们的东西——下一章会有更精确的定义。虚假的华夫饼和离婚相关性是一种混淆，南方性使得一个没有真正重要性的变量（华夫饼屋密度）看起来很重要。但混淆是多种多样的。它们可以像制造虚假效果一样容易地隐藏重要效果。

 (2) 多重复杂的因果关系。一个现象可能由多个同时发生的原因引起，并且原因可以以复杂的方式级联。由于一个原因可以隐藏另一个原因，因此必须同时测量它们。

 (3) 交互效应。一个变量的重要性可能取决于另一个变量。例如，植物受益于光和水。但是在没有任何一个的情况下，另一个根本没有好处。这种相互作用经常发生。对一个变量的有效推断通常取决于对其他变量的考虑。

## 5.1 虚假的联系


## 5.2 被掩蔽的关系


## 5.3 定类变量


