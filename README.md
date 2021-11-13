# matrix-
#include<iostream>
using namespace std;

int main()
{
   float t,a, A[3][3], B[3][3],C[3][3];

   cout<<"Enter the number of row =0 , <3 : ";
   cin>>t;

   cout<<"Enter the number of column =0 , <3 : ";
   cin>>a;



    cout << "please enter number 1st matrix: ";

    for (int i = 0;i<t;i++ ) 
    {       
        for (int j = 0;j < a;j++ ) 
        {

        cin>>A[i][j];

        }
    }

    cout << "please enter the number 2st matrix: ";

    for (int i = 0;i<t;i++ ) 
    {
        for (int j = 0;j<a;j++ ) 
        {

        cin>>B[i][j];

        }
    }

    cout<<"Output: ";

    for (int i = 0;i<t;i++ ) 
    {
        for (int j = 0;j<a;j++ ) 
        {

            C[i][j]=A[i][j]+B[i][j];

            cout<<C[i][j]<<" ";

        }
    } 
    cout<<endl;
   return 0;
}
