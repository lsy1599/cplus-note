###标准的vector
vector便是对象的集合，其中所有对象的类型都是相同的。集合中所有对象都有一个与之对应的索引，vector也称为容器。
vector是模板而不是类型，类似java中的泛化
vector后面跟一对尖括号，是vector内所存放对象的类型：
```c++
vector<int> ivec;
vector<Sales_item>			//保存Sales_item类型的对象
vector<vector<string>>		//该向量的元素是vector对象

```