# Divisiblity-HackerEarth-Solution
Divisiblity | HackerEarth | Solution (C++ code)

#include <iostream>
#include<string.h>
using namespace std;

int main() {

    int N = 0;
    cin>>N;
    string ans;
    
    long data[N];
    for(auto i=0; i<N; i++)
       {
            cin>>data[i];
    
    
    // write your code here
    // ans = 
      data[i] = data[i] % 10;
       }
       if(data[N-1]==0)
       ans = "Yes";
       else
       ans = "No";
    
    cout<<ans;
    
    return 0;
}


by VISHAL RAJ
CONTRIBUTER
