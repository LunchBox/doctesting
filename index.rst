
* 这是一个项目符号列表.
* 它有两项，
  第二项使用两行.

1. 这是个有序列表.
2. 也有两项.

#. 是个有序列表.
#. 也有两项.


* 这是
* 一个列表

  * 嵌套列表
  * 子项

* 父列表继续


术语 (term 文本开头行)
   定义术语，必须缩进

   可以有多段组成

下一术语（term）
   描述.


| 这些行
| 在源文件里
| 被分隔的一模一样.




这是一段正常文本. 下一段是代码文字::

   它不需要特别处理，仅是
   缩进就可以了.

   它可以有多行.

再是正常的文本段.



+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+






=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======




段落里包含 `a link`_.

.. _a link: http://example.com/






=================
This is a heading
=================





.. function:: foo(x)
              foo(y, z)
   :module: some.module.name

   返回用户输入的一行文本.




.. image:: gnu.png
   (选项)



.. image:: gnu.*




Lorem ipsum [#f1]_ dolor sit amet ... [#f2]_

.. rubric:: Footnotes

.. [#f1] 第一条尾注的文本.
.. [#f2] 第二条尾注的文本.




Lorem ipsum [Ref]_ dolor sit amet.

.. [Ref] 参考文献, 书,URL 等.



.. |name| replace:: replacement *text*



.. |caution| image:: warning.png
             :alt: Warning!



.. 这是一个评论.



..
   这整个缩进块都是
   一个评论.

   仍是一个评论.
