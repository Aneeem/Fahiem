#include <iostream>

using namespace std;

int main()
{
     int n;
    cout<<"Enter The Size of Input : ";
    cin>>n;
    int *x = new int[n];


    for(int i = 0;i<n;i++){
        cout<<"Assign the value to the " << i+1 <<" Array element = ";
        cin>>x[i];
    }
    cout<<"Print all the values of array element "<<endl;
    for(int i = 0;i<n;i++){
         cout<<x[i]<<endl;
    }
    delete [] x;

    return 0;
}
