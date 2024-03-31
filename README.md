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
# make a program that ask input in seconds and converts the number into days hour mints and sec value (10)
```
#include <iostream>
using namespace std;
int main(){
int sec,hour,day,mint;
int seconds=0;
cout<<"enter your value in seconds:";
cin>>sec;
day= sec/ (24 * 3600);
hour= (sec% (24 * 3600)) / 3600;
mint= sec % (24 * 3600) / 60;
seconds= (sec % (24 * 3600)) % 60;
cout<<"day:"<<day<<"hour:"<<hour<<"mint:"<<mint<<"sec:"<<seconds;
return 0;
}
```
# make a program that ask for year as an input and tells whather the year is a leap year or not (11)
```
#include <iostream>
using namespace std;
int main(){
int year;
cout<<"enter year:";
cin>>year;
if ((year%4==0) && (year%100!=0))  
    cout<<"ur year is a leap year";
else
    cout<<"ur year is not a leap year";
return 0;
}
```
# make a program that ask for your weight and height and calucalte the BMI (12)
```
#include <iostream>
using namespace std;
int main(){
float weight,height,bmi=0;
cout<<"enter your weight in lb:";
cin>>weight;
cout<<"enter your height in inch:";
cin>>height;
bmi=weight/(height*height)*703;
if (bmi>=18.5 && bmi<=25){
    cout<<"optimal weight    BMI:"<<bmi;
 }
 else if (bmi<18.5){
 cout<<"under weight   BMI:"<<bmi;
} 
else 
 cout<<"over weight   BMI:"<<bmi;
return 0;
}
```
# make a loop of natural numbers (13)
# chat bot (14)
```
#include <iostream>
#include <string>
using namespace std;
int main(){
    //introduction from user
    string name;
    cout<<"hi user plzz introduce yourself!!"<<endl;
     cout<<"lets start with ur name -->:";
      cin>>name;
       cout<<"hi "<<name<<endl;
    // ask for more info
     cout<<"well "<<name<<" tell me more about yourself"<<endl;
      cout<<"lets start with your age"<<endl;
    int age;
     cout<<"tell me how old are you "<<name<<" :";
     cin>>age;
    if (age>=14){
        cout<<"ohh so your a teenager"<<endl;
    }
    else if (age>=20){
      cout<<"so your a grown adult"<<endl;
    } else 
       cout<<"ohh so your a kid"<<endl;
    // ask for nationality
    string national;
     cout<<"well "<<name<<" what's your nationality:";
      cin>>national;
        cout<<"good to hear about you indeed "<<national<<" is a great place.";
      //ask user to play a game
    
}
```
