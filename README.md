# Integer-Comparing-program
In this program we have crea a c++ code which can be used to compare 3 integrs which are given as input 
Code is given below. Code is written using vscode.

..................................................................................................................
#include<iostream>
#include<math.h>
using namespace std;
int main(){
    int x, y,z;
    cout<<"Enter no.1:"<<endl;
    cin>>x;
    cout<<"Enter no.2:"<<endl;
    cin>>y;
    cout<<"Enter no.3:"<<endl;
    cin>>z;
    if (x<=y)
    {
        if (z<=y)
        {
            cout<<"no.2 is the greatest among three"<<endl;
        }
        
    }
    if (y<=z)
    {
        if (x<=z)
        {
            cout<<"no.3 is the greatest among three"<<endl;
        }
        
    }
    if (z<=x)
    {
        if (y<=x)
        {
            cout<<"no.1 is the greatest among three"<<endl;
        }
        
    }
    return 0;
    
    

}

...............................................................................................................
