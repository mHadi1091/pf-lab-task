# pf-lab-task
prgramming fundamentals lab work &amp; activity
## make a user based program and print the avg of the given values (01)
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

 ## write a user base program based on arthimatics operations (02)
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
     int a=x;
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
