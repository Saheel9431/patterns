
         * 
        * * 
       * * * 
      * * * * 
     * * * * * 
    * * * * * * 
   * * * * * * * 
  * * * * * * * * 
 * * * * * * * * * 
* * * * * * * * * * 

#include<iostream>
using namespace std;
int main()
{
    int num;
    int i=1;
    cout << "Enter a Number : ";
    cin >> num;
    for(int rows=0; rows<num; rows++)
    {
        for(int sp=0; sp<num-i; sp++)
        {
            cout << " ";
        }
        for(int col=0; col<=rows; col++)
        {
            cout << "*";
            cout << " ";
        }
        cout << endl;
        i++;
    }
}
