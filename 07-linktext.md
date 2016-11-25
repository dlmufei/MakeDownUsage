超链接
====
## 行内式
格式为 [link text](URL 'title text')。
* 普通链接：[Google](http://www.google.com/)
* 指向本地文件:[04-list.md](./04-list.md)
* 包含提示 'title' 的链接:[Google](http://www.google.com/ "Google")

----
## 参考式
参考式链接的写法相当于行内式拆分成两部分，并通过一个 识别符 来连接两部分。参考式能尽量保持文章结构的简单，也方便统一管理 URL。
1. 定义链接
> `[Google][link]`:
第二个方括号内为链接独有的 识别符，可以是字母、数字、空白或标点符号。识别符是 不区分大小写 的；
2. 然后定义链接内容
> `[link]: http://www.google.com/ "Google"`
3. 合成
> [Google][link] 

>[link]:http://www.google.com/ "Google"

4. 也可以省略 识别符，使用链接文本作为 识别符：
>`[Google]: http://www.google.com/ "Google"`

>[baidu]

> [baidu]: http://www.baidu.com/ "baidu"

---
## 自动链接
使用 <> 包括的 URL 或邮箱地址会被自动转换为超链接：
* > <https://www.baidu.com>
* > <10001@qq.com>


