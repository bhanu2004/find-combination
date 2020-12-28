// find-combination
#include <iostream>

using namespace std;
int factorial(int n){
    int fac=1;
    for(int i=1;i<=n;i++){
        fac=fac*i;
    }
    return fac;
}

int main()
{   
    int n,r;
   cout<<"enter the numbers: ";
   cin>>n>>r;
   int comb=factorial(n)/(factorial(n-r)*factorial(r));
  cout<<comb;
  
    return 0;
}
