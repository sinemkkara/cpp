#include <iostream>

using namespace std;

typedef struct Student{
	int number;
	string name;
	
}Student;
int main(){
	Student student1;
	Student *ptr1;
	cout<<"enter student number and name";
	cin>>student1.number>>student1.name;
	ptr1=&student1;
	cout<<"------------"<<endl;
	cout<<"student number :"<<student1.number<<endl;
	cout<<"student name   :"<<student1.name<<endl;
	
	cout<<"------------"<<endl;
	
	//pointer kullanarak erişme
	cout<<"student number :"<<(*ptr1).number<<endl;
	cout<<"student name   :"<<(*ptr1).name<<endl;
	
	cout<<"------------"<<endl;
	
	cout<<"student number :"<<ptr1->number<<endl;
	cout<<"student name   :"<<ptr1->name<<endl;
	
	
	
	
}
