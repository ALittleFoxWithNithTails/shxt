一级标题（#  内容）

二级标题（## 内容）

三级标题（### 内容）

四级标题（#### 内容）

五级标题（##### 内容）

六级标题（###### 内容）



普遍输入的内容



- -或者*代表的是圆点表示的是无序列表
- 按回车自动，两次回车取消



1. 代表有序列表，只需要直接数字.空格
2. 按回车自动，两次回车取消



 引用一小段别处的句子,只需要>  就行效果如本句两次回车消除





图片：！

 本地图片可以直接拖入



网页图片可以通过图床如上









插入链接：

Baidu 

 







表格：

  A班      	B班  	C班  
  使用\|符号划线	    	    





代码使用``进行包裹,使用 tab 键即可缩进

package com.shxt.model;

public class User {

    private String account;
    private String userName;
    public String getAccount() {
    	return this.account;
    }
    public void setAccount( String account ) {
    	this.account = account;
    }
    public String getUserName() {
    	return this.userName;
    }
    public void setUserName( String userName ) {
    	this.userName = userName;
    }
    @Override
    public String toString() {
    	return "User [account=" + this.account + ", userName=" + this.userName + "]";
    }

}



分割线三个以上的星号，减号，底线

三个*

---

三个_

---

三个-

---





Markdown 使用星号（*）和底线（_）作为标记强调字词的符号，被 * 或 _ 包围的字词会被转成用 <em> 标签包围，用两个 * 或 _包起来的话，则会被转成 <strong>，例如：

single asterisks

single underscores斜体

double asterisks

double underscores粗体



如果要在文字前后直接插入普通的星号或底线，你可以用反斜线：

    \*this text is surrounded by literal asterisks\*效果如下

*this text is surrounded by literal asterisks*





如果要标记一小段行内代码，你可以用反引号把它包起来``，例如：

    Use the `printf()` function.

Use the printf() function.





Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：

    \   反斜线
    `   反引号
    *   星号
    _   底线
    {}  花括号
    []  方括号
    ()  括弧
    #   井字号
    +   加号
    -   减号
    .   英文句点
    !   惊叹号


