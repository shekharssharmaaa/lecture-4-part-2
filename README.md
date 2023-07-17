#include<iostream>
using namespace std;
 
int main()
{
float a,b;
cout<<"Give 2 floating point numbers as input"<<endl;
cin>>a>>b;
if(a>0.01&& b>a)
{
    cout<<"The condition in if statement is correct";
    
}
else
{
    cout<<"The condition is false ";
}
}



#include<iostream>
using namespace std;
 
int main()
{
int marks;
cout<<"Student,please enter the maarks to calculate the grade:";
cin>>marks;
 if(marks>90)
{
     cout<<"A";
}
else if(marks<90 && marks>80)
{
    cout<<"B";
}
else if(marks<80 && marks>70)
{
    cout<<"C";
}
else(marks<70)
{
    cout<<"Pass";
}
}




#include<iostream>
using namespace std;
 
int main()
{
int  a,b,c,d;
cout<<"Give three integers as input : a,b,c"<<endl;
cin>>a>>b>>c>>d;
if(a>b && c>d)
{
    cout<<"haha";
}
else if(a>b && c<d)
{
    cout<<"hehe";

}
else(a<b && c>d)
{
    cout<<"huhu";
}




#include<iostream>
using namespace std;
 
int main()
{
int  a;
cout<<"enter a integer a";
cin>>a;

switch (a)
{
    case1:
    cout<<"The value of a is 1";
    break;
    case2:
    cout<<"The value of a is 2";
    default:
    cout<<"default will always printed";
    break;
    
}
}
