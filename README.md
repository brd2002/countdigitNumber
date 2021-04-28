# countdigitNumber
code is implemented in c++;
      #include<iostream>
#include<limits.h>
using namespace std;
int countDigit(int n)
{
    int res =0;
    while(n>0)
    {
        n = n/10;
        res++;
    }return res;
}
int main()
{
    int n;
    cin>>n;
    cout<<countDigit(n);
    return 0;
}

//code with brd coder007  
