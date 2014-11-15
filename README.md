string_cin.get
==============


#include <iostream>
#include <iomanip>    //for setw


using namespace std;


const int MAX =80;   //MAX CHARACTERs in string
char str[MAX];   //string variable str

int main()
{

    
    cout<<"\nEnter a string:";
    cin.get(str,MAX,'$');
    cout<<"You Entered:"<<str<<endl;
    return 0;
}
