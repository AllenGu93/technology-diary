---
title: 小方法拾记——mb_strlen
date: 'Wed, 16 Jan 2019 11:25:57 +0800'
stacks: []
---

mb_strlen用于计算字符串的长度，与strlen的区别是：对于汉字的长度计算。strlen将中文字符计算为3个长度，mb_strlen计算为1个。

> 应用场景

计算用户名长度限制时一定要用mb_strlen,其他字符长度限制也要酌情考虑是否应该将中英文长度一视同仁。


