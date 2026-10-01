# Calculate-Gross-Salary
C++ program to calculate TA, DA, HRA, and gross salary from the basic salary.
#include <bits/stdc++.h>
using namespace std;
int main(){
    float bs,ta,da,hra,gross;
    cout<<"Enter basic salary:";
    cin>>bs;
    ta=bs*20/100;
    da=bs*30/100;
    hra=bs*40/100;
    gross=bs+ta+da+hra;
    cout<<endl;
    cout<<"the ta is:"<<ta<<endl;
    cout<<"the da is"<<da<<endl;
    cout<<"the hra is"<<hra<<endl;
    cout<<"the gross salary is"<<gross<<endl;
    return 0;
}
