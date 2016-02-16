// getting-started
#include<iostream.h>
#include<conio.h>
class add
{
public:
int a,b;
void getvalues()
{
cout<<"Enter 1st number";
cin>>a;
cout<<"Enter 2nd number";
cin>>b;
}
friend void addition(add ad);
};
void addition(add ad)
{
cout<<"Sum of 2 numbers is <<ad.a+ad.b;
}
int main()
{
add ad;
ad.getvalues();
addition(ad);
getch();
}
