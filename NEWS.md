# Release Notes
This file records the main changes in *PyLf* library in reverse chronological order.

## in progress version
* **改进算法使得参数*text*可为*iterable***

## v0.4.0 (2017-12-5)
* Add *ValueError* raised by *pylf.handwrite()* to prevent dead loop in some corner cases
* Improve docstring
* **将黑色作为*template*的缺省颜色**
* **字体宽度从由*font_size*决定改为由每个字符自己的信息决定**
* **将(lambda c: False)作为*template*的缺省*is_half_char***
* **将是否在常见非开头字符集中作为*template*的缺省*is_end_char***