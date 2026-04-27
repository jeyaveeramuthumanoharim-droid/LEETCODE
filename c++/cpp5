#include<iostream>
using namespace std;
class student
{
   int clg,reg;
   public:
   student()
   {
      clg=0;
   }
   student(int a)
   {
      clg=a;
   }
   student(student &x)
   {
      clg=x.clg;
   }
   void getdata()
   {
      cout<<"enter a REGISTER NUMBER:";
      cin>>reg;
   }
   void display()
   {
      cout<<"COLLEGE CODE:"<<clg<<endl;
   }
   ~student()
   {
   }
};
int main()
{
   student s1(112);
   student s2(s1);
   student s3=s1;
   s1.getdata();
   s1.display();
   s2.getdata();
   s2.display();
   s3.getdata();
   s3.display();
   return 0;
}
