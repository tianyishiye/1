# JAVA实验报告
班级：计G191
姓名 : 邓嘉睿
   学号：2019322044
实验目的:
掌握字符串String及其方法的使用
掌握异常处理结构。



</p>
<p>实验过程：
创建项目
创建项目
定义数组
抛出异常
判断



</p>
<p>核心代码：
Scanner scanner=new Scanner(System.in);
         int result=0;
         int status=0;
         System.out.println("请输入文章:");
         String article=scanner.next();
         while(status==0){
             System.out.println("请输入需要查询的字符:");
             String str=scanner.next();
             for(int i=0;i&lt;article.length();i++){
                 String newArticle=article.substring(i,i+1);
                 if(newArticle.equals(str)){
                     result++;
                 }
             }






</p>
<p>运行截图：





</p>
<p>编程感想总结：
通过这次实验，我意识到了自己在JAVA方面学习的不足和对于新的知识接受效率的缺陷。对于代码方面的知识让我焦头烂额，通过网络资料和课本JAVA语言程序设计，我学到了很多以前不知道的东西。有两种方法可以做到：
1 用制表符\t实现对齐。
制表符\t输出的时候，会移动输出光标，实现对齐效果。所以可以在输出的对应位置，增加\t来实现对齐。
要求每行相同列输出占用空间差别不可以太大。

</p>
<p>2 在格式字符中加入占用宽度控制数字。
C语言使用printf输出时，每个控制字符均可以写成
%nC的形式，如%10d, %12f, %8c, %16s等等。
其效果就是输出对应变量时占用n个字符的宽度。不足部分左侧补空格。通过这种方式，可以实现右对齐效果。
如果要实现做对齐效果，只需要在宽度字符前加-符号即可，如%-8s，就是把字符串输出，占8位宽度，右侧补空格。
Edit By <a href="http://mahua.jser.me">MaHua</a></p>
</body></html>
