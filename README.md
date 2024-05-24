# structsort
首先定义线程数目，其中num可按照要求规定为1,2,4,8,16
# define NUM_THREADS num
然后在虚拟机中创建一个文件夹用于存放程序文件
mkdir my_c++
然后进入该目录,创建名叫prestructsort的cpp文件
cd my_c++
touch prestructsort.cpp
然后在文件内写入已经编写好的程序
vim hello.cpp
在vim界面输入i，开始编写程序，程序编写好后按Esc键，输入：wq 完成编写并保存该文件
然后对该文件进行编译，得到名为structsort的文件
g++ -g prestructsort.cpp -o structsort
然后输入具体数值运行该程序，其中number_of_elements要处理的元素个数，本实验中选择10000
./struct-sort number_of_elements
然后重复上述操作，得到线程数改变后的结果，根据输出的Time Taken计算加速比
为了结果更加准确，每个线程数下执行两次，取平均值计算加速比
![image](https://github.com/YukangHou/structsort/assets/170058247/7f888ad9-89ca-4c58-814a-ddd89e1dc8ab)
