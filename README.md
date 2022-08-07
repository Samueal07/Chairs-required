// Chairs-required
#include <iostream>
using namespace std;

int main() {
	int t;
	cin>>t;
	for(t;t>=1;t--){
	    int x,y;
	    cin>>x >>y;
	    if(x>y){
	        cout<<x-y<<endl;
	    }
	    else if(x==y){
	        cout<<"0"<<endl;
	    }
	    else if (x<y){
	        cout<<"0"<<endl;
	    }
	return 0;
}}
