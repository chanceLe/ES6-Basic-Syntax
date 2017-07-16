###Welcome to use MarkDown
>1.扩展运算符（...）
>>[...{length:3}]  书上释义不能转换为数组，实测转换成功了。 
另一个地方，[...[1,,2]] 愿意是数组空位不会忽略，转换成undefined，实际上并没有
像Array.from那样转成undefined。

>2.Array.prototype.values()
// 这个方法实际上并不存在。但是可以直接for of 循环数组，与这个方法等价。