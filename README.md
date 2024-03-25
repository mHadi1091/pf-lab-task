# pf-lab-task
prgramming fundamentals lab work &amp; activity
# make a user based program and print the avg of the given values (01)
```
#include <iostream>
using namespace std;
int main(){
    int x,y,z,avg=0;
    cout<<"enter value of x=";
    cin>>x;
    cout<<"enter value of y=";
    cin>>y;
    cout<<"enter value of z=";
    cin>>z;
    avg=(x+y+z)/3;
    cout<<"total avg="<<avg;
    return 0;
}
* `OUTPUT`
* `enter value of x=54`
* `enter value of y=22`
* `enter value of z=21`
* `total avg=32`
```

 # write a user base program based on arthimatics operations (02)
 ```
#include <iostream>
using namespace std;
int main(){
    int x,y,z,a,b,c,d;
    cout<<"enter value of x=";
    cin>>x;
    cout<<"enter value of y=";
    cin>>y;
    cout<<"enter value of z=";
    cin>>z;
    a=x+y;
    b=x-y;
    c=x*y;
    d=x/y;
    cout<<"sum="<<a<<"\n";
    cout<<"submission="<<b<<"\n";
    cout<<"multiple="<<c<<"\n";
    cout<<"division="<<d<<"\n";
    return 0;
}
* `OUTPUT`
* `enter value of x=45`
* `enter value of y=13`
* `enter value of z=78`
* `sum=58`
* `submission=32`
* `multiple=585`
* `division=3`
```

# write a program that takes the radius of cricle from user and print its area (03)
```
#include <iostream>
using namespace std;
int main() {
  float pi=3.14159,r,area=0;
  cout<<"enter radius=";
  cin>>r;
  area=pi*r*r;
  cout<<"area of radius="<<area;
    return 0;
}
* OUTPUT
* enter radius=25.3
* area of radius=2010.9
```
# create a program that swaps the value of two variables. take the input of two numbers from the user and then swap their values (04)
```
#include <iostream>
using namespace std;
int main() {
    int x, y;
    cout << "Enter the value of x: ";
    cin >> x;
    cout << "Enter the value of y: ";
    cin >> y;

    cout << "Before swapping: x = " << x << ", y = "<< y << "\n";
    a=x;
    x=y;
    y=a;
    cout << "after swapping: x = " << x << ", y = "<< y;
    return 0;
}
* OUTPUT
* Enter the value of x: 5
* Enter the value of y: 6
* Before swapping: x = 5, y = 6
* after swapping: x = 6, y = 5
```
# make a program to convert temperature from celsius to fahrenheit the user should input the temperature in celsius (05)
```
#include <iostream>
using namespace std;
int main() {
float celsius, fahrenheit;
    cout << "Enter the temperature in Celsius: ";
    cin >> celsius;
    fahrenheit = (celsius * 9/5) + 32;
    cout << "temperature in fahrenhait:" <<fahrenheit;
    return 0;
}
```
# make a program which takes users age & tells them wether user is a child or teen (06)
```
#include <iostream>
using namespace std;
int main() {
int x;
cout<<"enter your age:";
cin>>x;
if (x>=14){
    cout<<"your a teen!"<<endl;
}
    else if (x<14)
    cout<<"your a chlid!"<<endl;

    return 0;
}
* OUTUPUT ( if user is a teen >14 )
- enter your age:15
- your a teen!
* OUTPUT ( if user is a child <14 )
- enter your age:9
- your a chlid!
```
# make a program that takes to values from the user and swap them with eachother (07)
```
#include <iostream>
using namespace std;
int main() {
int x,y,a;
cout<<"enter the value of x:";
cin>>x;
cout<<"enter the value of y:";
cin>>y;
cout<<"before swappping; x="<<x<<", y= "<<y<<"\n";
a=x;
x=y;
y=a;
cout<<"after swapping; x="<<x<<", y= "<<y<<"\n";
    return 0;
}
* OUTPUT
- enter the value of x:56
- enter the value of y:22
- before swappping; x=56, y= 22
- after swapping; x=22, y= 56
```
# swap the values of 2 int by using only 2 variables (08)
```
#include <iostream>
using namespace std;
int main() {
int a=10;
int b=20;
cout<<"before swapping a="<<a<<" ,b="<<b<<"\n";
a=10+20;
b=20-10;
a=30-10;
cout<<"after swapping a="<<a<<" ,b="<<b<<"\n";
    return 0;
}
* OUTPUT
- before swapping a=10 ,b=20
- after swapping a=20 ,b=10
```
# calculator (09)
```
#include <iostream>
using namespace std;
int main(){
    int num1 , num2 ;
    char keys;
    cout<<"enter your 1st value:";
    cin>>num1;
    cout<<"enter your 2nd value:";
    cin>>num2;
    cout<<"enter your operation:";
    cin>>keys;
    switch (keys){
        case '+': cout<<"answer:"<<(num1+num2); break;
        case '-': cout<<"answer:"<<(num1-num2); break;
        case '*': cout<<"answer:"<<(num1*num2); break;
        case '/': cout<<"answer:"<<(num1/num2); break;
        default : cout<<"invalid operation!!"; break;
    }
  return 0;
}
```
