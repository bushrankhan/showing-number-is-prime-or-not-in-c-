# showing-number-is-prime-or-not-in-c-
taking a input from the user and showing the number is prime or not using loops in c++
#include<iostream>
using namespace std;

int main() {
    #ifndef ONLINE_JUDGE
    freopen("input.txt", "r", stdin);
    freopen("output.txt", "w", stdout);
    #endif

int n;
cin>>n;
cout<<"ENTER A NUMBER"<<endl;
int i;
for ( i = 2; i < n; i++)
{
    if (n%i==0)
    {
        cout<<"non prime"<<endl;
        break;
    }  
}
if (i==n)
{
    cout<<"prime"<<endl;
}


    return 0;
}
