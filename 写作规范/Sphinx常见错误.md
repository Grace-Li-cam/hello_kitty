---
sort: 7
---

# Sphinx常见错误

1. Error parsing content block for the “list-table” directive: uniform …-level bullet list expected, but row … does not contain the same number of items as row … (… vs …)

原因：

使用 list-table:: 创建的表格每行必须有相同的列数（bullet list items） 。这个错误是提示第xx行的列数不对。

解决方法：

检查错误提示的表格。

2. Duplicate target name, cannot be used as a unique reference

原因：

引用链接指向多个目标对象。

解决方法：

检查错误提示的超链接格式是否有问题。

3. Image file not readable

原因：

Sphinx找不到图片指定的路径。

解决方法：

检查错误提示的图片路径是否正确。

4. Inline literal start-string without end-string

原因：

通常为 \``格式忘记加尾部的\``。

解决方法：

检查错误提示行的格式，补充丢失的\``。
