#include<iostream>
using namespace std;
int main(){
    int x,y;
    cout<<"pola = ";
    cin>>x;
    for(int i=1;i<=x;i++){
       for(int j=1;j<=x;j++){
       	if(i%2!=0){
       		if(j%2!=0){
       			cout<<"#";
			   }else{
			   	cout<<"o";
			   }
		}else{
			if(j%2!=0){
				cout<<"o";
			}else{
				cout<<"#";
			}
		}
	   }
    cout<<endl;}
}
