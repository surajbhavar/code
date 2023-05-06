# code
exception handling
#include <iostream>
using namespace std;
int main()

{
    int a,b,x;
    cout<<"enter a";
    cin>>a;
    cout<<"\nenter b";
    cin>>b;
    x=a-b;

try
{
    if (x!=0)
    cout<<"a/x="<<a/x;
    else
    {
        throw(x);
        
    }
}
catch(int p)
{
    cout<<"sorry divide by zero it is not working";
}
int d=10;
cout<<"\nd = "<<d;
return(0);
}
