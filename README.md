README
===========================
这是一个用Latex写的教案模板，基于 [xecjk-template](https://github.com/xiaohanyu/xecjk-template) 中文模板，
本教案模板符合本院的格式要求，首页采用表格制定格式，然后用制定指令替换里面的内容，
教案内容页用 TiKz 画了个带旁注的边框，制定了首页与教案内容的页眉，并对 Latex 默认的格式进行了设定。

****
###　　　　　　　　　　　　Author:高星
###　　　　　　　　　  E-mail:gnix.oag@gmail.com
===========================

##目录
* [使用方法](#使用方法)
* [新增指令](#新增指令)

###使用方法
*教案内容写在 data/sec1.tex  data/sec1.tex data/sec1.tex ... ...中；
*然后 \input 加入 main.tex 
*参考sec1.tex 编写内容，可正常使用 latex 指令使用，

###新增指令
*\jsxm{高老师} %教师姓名
*\jyszr{高星}	%教研室主任
*\jc{《加工中心编程与操作》刘加孝主编}%教材
*\cks{}%参考书
*\skbc{15级中数班}%授课班次
*\biaoti{理论}%标题头
*\jxhj{%教学后记}
*\skrq{%授课日期}
*\ktmq{%课题名称 }
*\jxmb{%教学目标，每行前面要加 \item}
*\jxzd{%教学重点，每行前面要加 \item}
*\jxnd{%教学难点，每行前面要加 \item}
*\jjff{%教学方法}
*\makeshouye %制作教案首页
