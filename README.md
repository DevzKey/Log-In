#include <iostream>
using namespace std;
int main(){
string un, pass;
int limit=0;

cout<<"WELCOME TO LOGIN PAGE";
cout<<"PLEASE INPUT YOUR USERNAME: ";
cin>> un;
cout<<"PLEASE INPUT YOUR PASSWORD: ";
cin>>pass;

//disregard this part this is a comment line
//change your un for the word anything you want

if(un=="user" && pass=="user"){
}else{
cout<<"WRONG USERNAME OR PASSWORD";
}

return 0;
}
