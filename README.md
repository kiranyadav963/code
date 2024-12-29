# code
#include <iostream>
using namespace std;
void countzeroone(int arr[] , int size){
  int zero=0;
  int one=0;
  for(int i=0; i<size ;i++){
    if(arr[i]==0){
      zero++;
    }
    if(arr[i]==1){
      one++;
    }
  }
  
    cout<<"no of zeroes: "<<zero<<endl;
    cout<<"no of ones: "<<one<<endl;
  
}
int main() 
{
    int arr[] = {0,1,0,1,1,0};
    int size = 6;
    countzeroone(arr,size);
}
