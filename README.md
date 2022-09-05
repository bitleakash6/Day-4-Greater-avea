#include <iostream>
using namespace std;

int main() {
	// your code goes here
  //greater average
	int t;
	cin>>t;
	int a,b,c;
	while(t--){
	   // float avg;
	    cin>>a>>b>>c;
	   
	    if(float(a+b)/2 > c)
	    {
	        cout<<"YES"<<endl;
	    }
	    else
	    {
	        cout<<"NO"<<endl;
	    }
	}
	return 0;
}
