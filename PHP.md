## PHP (Hypertext Prepocessor)

\-server上执行\
\-包文本：html,javascript,php代码\
\-生成“动态页面”内容\
\-收集表单书数据\
\-use on Windows,Linux,Unix,MacOS\
\-can create, open,read,write, close file on server\
\-add, delete data in database\
\-encrypt

#### 客户端+服务器

**client—>Web server(receive request,action:accept or reject then execute)—>forward (html+jss+css) to client**

客服端+服务器（小皮Apache）(一体)</br>
网站，页面</br>
本质：文件(.php)->文本文件（apache解析）动态计算</br>
URL is like the path to directories

\<?php open

<p>?>     close </p>

to comment:
// for single line comment
/*
*/ for many line comment

each line of code much always end with **;**

variable in PHP can only have letter,underscore and numbers</br>
$_a564="onetothree";

$A != $a

#### 4 types of variables:

\-global</br>
\-local</br>
\-static</br>
\-parameter</br>

**PHP variable(变量):**
1. echo  
2. print  
3. print_r  
4. var_dump = dump information about a variable

**var_dump is use for debug**

**Example:**  
<\?php  
name="mashibing";  
a=array("Toyota","BMW","Tesla");  
echo a；   **//array**</br>
echo "\</br>"; </br>
print (a);   **//array**</br>
echo "\</br>";  </br>
print_r(a);   **//array([0]=>Toyota[1]=>BMW[2]=>Tesla)**
echo "\</br>"; </br>
var_dump(a);   **//array(3){[0]=>string)(6)"Toyota"[1]=>string(3)"BMW"[2]=>string(5)"Tesla"}** </br>
var_dump($name);   **//string(9)"mashibing"**

**PHP data types comparision 数据类型比较:**
1. String 字符串 -> characters
2. Integer 整型 -> whole numbers positive and negative
3. Float 浮点型 -> decimal value
4. Boolean 布尔型 -> 真假，01，TrueFalse
5. Array 数组
6. Object 对象 -> 函数
7. NULL 空值 -> 0, "", NULL
8. Resource 资源类型 -> image, files

**== 比较值，不比较类型**  
**=== 比较值和类型**

x=0x86; 十六进制数  
x=047; 八进制数

**echo 显示**  
**return 放回但不显示**

**PHP constant 常量:**

盒子里数据固定的

define("名字","值","大小写敏感")  
define(string,value,bool$case_insensitive)

header(content-type:text.html;charset=utf-8);

**Example:**  
\<?php  
define("GREETING","欢迎"，true);  
echo GREETING;  
echo "\</br>";  
echo greeting;
