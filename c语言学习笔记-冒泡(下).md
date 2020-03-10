##*C语言学习笔记——算法——冒泡排序*
###三、错误程序及解决方案：
###错误二——修正：

      #include <iostream>
      #include <vector>    //必要头文件 
      using namespace std;
      vector <int> a;    //定义动态数组 
      int main() {
      for(int i = 1;i <= 200;i ++) a.push_back(i);    //类似队列的数组元素插入 
      a.pop_back();    //删除末尾元素 
      cout << a.size() << endl;    //输出数组大小 
      for(int i = 0;i < 199;i ++) cout << a[i] << endl;    //输出所有元素
待测试；

###体会：c语言学习的路还很长，c语言很重要，不会的东西很多，钻研的时间很少，学习总是断断续续，又不爱记笔记，荒废了很多，以后每天尽量抽出时间弥补，也应结合单片机以应用为主。



