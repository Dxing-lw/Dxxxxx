# <center> <font face='仿宋' font color=orange>   Markdown入门教程    </font>

## <center>  <font face='楷体' size=5 >   Xing.    </font>
<!-- TO DO: add more details about me later 添加注释 -->
### 一、准备工作

1. **安装VSCODE**
   [vscode官方网站]  <https://code.visualstudio.com/>
2. **下载必要的插件**
-Markdown All in one
-Markdown Priview Enhance
-Markdown PDF
-Paste Image
3. **创建.md文档，打开同步预览功能，开始编辑**

### 二、基本语法

1. **标题**
    #一级标题
    ##二级标题
    ...
2. **引用**
    > 编辑这类文档注释
    >> 注释(嵌套)

3. **列表**
    1. 无序列表
    - 列表1
    - 列表2
    - 列表3
  
    2. 有序列表
       1. X1
       2. X2
       3. X3

    3. 列表嵌套
        1. xxx
        2. xxx
    4. todolist
        - [x] A
        - [ ] B
        - [ ] C
4. **表格**

    | 左对齐 | 居中对齐 | 右对齐 |
    | :----  | :----: | ----: |
    | a | b | c|
    |d | e | f |

5. **段落**
   - 换行 ？ 两个以上空格后回车/空一行  
     abc
   - 分割线 -- 3个*
    ***
    - 字体

        | 字体 | 代码 |
        | :--:  | :--: |
        | *斜体* | ** |
        |==高亮== | == == |
        |**粗体** |****|
        |***粗斜体***| ******|
        |~~删除线~~|~~ ~~|
        |<u>下划线</u>| ```<u>  </u>```|

    - 脚注
        点赞[^1]支持
6. **代码**
若要为创建的表创建折叠部分，请将表包装在 <details> 标记中，如以下示例所示。

<details open>
<summary>My top THINGS-TO-RANK</summary>
默认打开状态
YOUR TABLE
</details>
<details>
<summary>My top languages</summary>

| Rank | Languages |
|-----:|-----------|
|     1| JavaScript|
|     2| Python    |
|     3| SQL       |

</details>

```
#include<stdio.h>
using namespace std;
int main(){
     print("hello word");
}
```

    `print(“hello);`
7. **超链接**
    - [更多使用方法]： <http://www.runoob.com/>
    - 相关消息[点击链接][教程]
8. **图片**
    - 使用图床保存图片并插入
        [路过图床]: <https:/imgse.com/>
    - 使用markdown语法插入
    [![pFZHwAe.jpg](http://s11.ax1x.com/2024/01/23/pFZHwAe.jpg)](http://imgse.com/i/pFZHwAe)
    - 或者使用html语言
    <a href="http://imgse.com/i/pFZHwAe"><div align=center> <img src='http://s11.ax1x.com/2024/01/23/pFZHwAe.jpg' alt='xq.jpg' width="80%" hight="60%"/></div></a>

### 三、其他操作

- **插入latex公式**
  - 行内公式
    $f(x)=ax+b$
    - 块内显示数学公式
    $$
    \begin{Bmatrix}
    a & b \\
    c & d \\
    \end{Bmatrix}
    $$
- **html/css语法**
- ctrl+shift+p 搜
- "Markdown Preview Enhanced:Customize CSS"
    在style中使用css语法改标题格式等
- **个性化设置**
        file - preferences -setting

### 四导出为pdf文件

- 使用markdown PDF
- Open in Browser - 手动另存为pdf

[教程]: <http://www.runoob.com/>
[^1]: 点赞
