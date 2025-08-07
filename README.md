class Person
{
public:
	void Print()
	{
		cout << "name:" << _name << endl;
		cout << "age:" << _age << endl;
	}
protected:
	string _name = "peter"; // 姓名
	int _age = 18; //年龄
};
 
 
继承上面的类：  : + 类名 ，public是一种继承方式
class Student : public Person
{
protected:
	int _stuid; // 学号
};
 
class Teacher : public Person
{
protected:
	int _jobid; // 工号
};
 
int main()
{
	Student s;
	Teacher t;
 
	s.Print();
	t.Print();
 
	return 0;
}
