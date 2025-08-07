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
 https://github.com/ylsxhz
https://github.com/tbhtyyy
https://github.com/kkwis
https://github.com/fsgrla
https://github.com/dwbdsh
https://github.com/dtzwl
https://github.com/wxgsnds
https://github.com/rytzsm
https://github.com/txplts
https://github.com/jmssmy
https://github.com/wgtla
https://github.com/ktddbqd
https://github.com/znhpx
https://github.com/yldcj
https://github.com/yldcj/yldcj
https://github.com/yldcj/yldcj/issues/1
https://github.com/bookmins/tio
https://github.com/bookmins/iu
https://github.com/bookmins/cp
https://github.com/nmszgb/ywjd
https://github.com/huiyae/mo
https://github.com/huiyae/bo
https://github.com/huiyae/vo
https://github.com/ndxywz/dzn
https://github.com/ndxywz/gsd
https://github.com/ndxywz/nsp
https://github.com/feridr/bo
https://github.com/mghekl/vop
https://github.com/feridr/shiba
https://github.com/feridr/co
<img width="563" height="1202" alt="image" src="https://github.com/user-attachments/assets/0588b781-6662-480e-bcc0-a8e44da8d9ec" />

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
