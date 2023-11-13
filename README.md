GZHU grade 10 program design basic experiments personal backup.  
======
This repository is created for personal backup.  
Highly NOT recommand using codes in this repo to submit homework.  

experiment 1  
----
* A-1  
    从键盘上输入两个int型数，比较其大小，并输出显示其中较小的数。  
* A-2  
    从键盘上输入一个int型数、一个浮点数，比较大小，将其中较大的数输出。  
* A-3  
    输入一摄氏温度，编程输出华氏温度。已知；华氏温度转换为摄氏温度的计算公式如下： C=5/9*(F-32)，其中，F 表示华氏温度，C表示摄氏温度；结果保留两位小数。  
* A-4  
    输入一个大于1000的int型数，将它的低4位(右四位)都置为1。  
* B-1  
    有一个函数：  
Y = x when x<=0, 5x-10 when 0<x<10, 10x-20 when x>=10  
    用cin输入函数输入x的值（分别为x<=0，0<x<10，x>=10），输出y的值。  
* B-2  
    给出一个不多于4位的正整数，要求：（1）求出它是几位数；（2）分别输出每一位数；（3）按逆序输出各位数字，例如原数为2560，应输出为0652。  
* C-1  
  求1+2+···+100    
  方法一：用while语句编程。  
  方法二：用do-while语句，求1到100的和。  
  方法三：用for语句编程。  
* C-2  
  先由计算机“想”一个1～200之间的数请人猜，如果人猜对了，在屏幕上输出人猜了多少次才猜对此数，以此来反映猜数者“猜”的水平，则结束游戏；否则计算机给出提示，告诉人所猜的数是太大还是太小，最多可以猜10次，如果猜了10次仍未猜中的话，则停止本次猜数，然后继续猜下一个数。每次运行程序可以反复猜多个数，直到操作者想停止时才结束。
  
experiment 2  
-----
* 1  
    求三角形的面积。已知三角形的三边a、b、c，则三角形的面积为 area=[s(s-a)(s-b)(s-c)]^1/2，其中，s=(a+b+c)/2。  
    （1）三角形的三边的边长由cin输入，需要判断这三边是否构成一个三角形。若是，则计算其面积并输出，否则输出“错误：不能构成三角形！”。  
    （2）程序中要包含两个函数，一个函数判断是否构成三角形，另一个函数计算三角形的面积。  
* 2  
  编程求下式值，其中ni用函数来实现，且设参数n的默认值为2：n^1+n^2+n^3+n^4+⋯+n^10， n=1,2,3  
* 3  
  用递归法将一个整数n转换成字符串。如输入1234，应输出字符串“1234”。n的位数不确定，可以是任意位数的整数。  
* 4  
  编写程序，计算下面公式并输出结果。nCm=n!/(n-m)!m!  
  (1)编写一个函数计算n!  
  (2)编写主函数，由键盘输入n和m，调用（1）中的函数完成计算。  
  (3)输入n和m要给出提示，并检查n和m的合理性，不合理的输入应输出错误信息，并不再进行计算。  
  (4)运行程序，输出计算8C5,5C2,7C0。
  
experiment 3  
------
* A-1 //unfinished  
  某班期末考试科目为数学（MT）、英语（EN）和物理（PH），有最多不超过30人参加考试。考试后要求：  
  （1）计算每个学生的总分和平均分；  
  （2）按总分成绩由高到低排出成绩的名次；  
  （3）打印出名次表，表格内包括学生编号、各科分数、总分和平均分；  
  （4）任意输入一个学号，能够查找出该学生在班级中的排名及其考试分数。  
* A-2  
  不用字符串处理函数将两个字符串连接，即将字符串b连接到字符串a的后面，变成字符串c。  
* B-1  
  定义一个结构变量（包括年、月、日），计算该日在本年中为第几天？（注意考虑闰年问题），要求写一个函数days，实现上面的计算。由主函数将年月日传递给days函数，计算后将日子传递回主函数输出。  
* B-2 //unfinished  
  编写一个程序，用结构表示一个学生的信息，每个学生的信息包括：学号、姓名、三门成绩。要求从键盘输入学生的数据，并输出成绩表（包括每个学生的学号、姓名、三门成绩及平均分数），并输出平均分在前3名的学生的姓名及平均分。  
* C-1  
  要求使用指针处理下面的问题，输入四个整数，按由小到大的顺序输出；然后将程序改为：输入四个字符串，按由小到大顺序输出。（使用指针或指针数组）  
* C-2  
  通过指针和动态存储处理下面的问题：利用随机函数模拟产生300个1~12月出生的人数，统计本次运行得到的数据中，各个月的出生率是多少。
  
experiment 4  
----
* 1  
  掷骰子游戏：编写程序模拟掷骰子游戏。已知掷骰子游戏的游戏规则为：每个骰子有6面，这些面包含1、2、3、4、5、6个点，投两枚骰子之后，计算点数之和。如果第一次投的点数和为7或11，则游戏者获胜；如果第一次投的点数和为2、3或12，则游戏者输；如果第一次投的点数和为4、5、6、8、9或10，则将这个和作为游戏者获胜需要掷出的点数，继续投骰子，直到赚到该点数时算是游戏者获胜。如果投掷7次仍未赚到该点数，则游戏者输。  
* 2  
  如果将游戏规则改为：计算机“想”一个数作为一个骰子掷出的点数（在用户输入数据之前不显示该点数），用户从键盘输入一个数作为另一个骰子掷出的点数，再计算两点数之和。其余规则相同，然后请重新编写该程序。  
* 3
  要求能够运用多文件程序完成一个完整的程序功能操作流程。  
  输入一串字符，再输入一个指定字符，将字符串中删去指定字符再显示出来。要求程序把输入字符串、删除指定字符和显示字符串的功能分别在各自单独的.cpp文件中由外部函数来处理，主文件中的主函数只作调用各外部函数实现程序功能。  
