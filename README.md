#include<iostream>
#include<string>
using namespace std;
class student{
	string name;
	int age;
	int roll;
	public:
	student() {
		cout<<"enter student details"<<endl;
	}
	
	void set(string name) {
		this->name=name;
	}
	
	void setter(int age) {
		this->age=age;
	}
	
	void getter() {
		cout<<"age= "<<age<<endl; 
	}
	
	void get() {
		cout<<"student name = "<<name<<endl;
	}
};
int main() {
	student obj;
	obj.set("ilma");
	obj.setter(20);
	obj.get();
	obj.getter();
}
