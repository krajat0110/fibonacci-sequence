# fibonacci-sequence
#include<iostream>
using namespace std;

int main(){

int n;
cin>>n;

int a =0,b=1,sum=0,cnt=0;
 while(cnt<n) {
       cout<<a<<endl;
      sum=a+b;
       a=b;
      b=sum;
      cnt=cnt+1;
 }
}
