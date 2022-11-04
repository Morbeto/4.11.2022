# 4.11.2022
// ConsoleApplication25.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
using namespace std;

int main()
{ /*task1
   int a;
    do {
        cin >> a;
    } while (a >= 100 || a  < 10);
  */
  /*task3
  int n;
  cout << "Enter n : ";
  cin >> n;
  for (int sum = n; sum > 1; --sum) {
      n *= sum - 1;
  }
  cout << "The sum is : " << n << endl;
  */
  /*task4
  int first , second , third;
   for (int number = 100;number < 1000 ; number++) {

       first = number / 100;
       second = (number / 10) % 10;
       third = number % 10;
       if (first != second && first != third)
       {
           if (second != third) {
               cout << number << endl;
           }
       }


   }
  */
    /*task 5
    int first, second, third;
    int sum;
    for ( int number = 100; number < 1000; ++number) {

        first = number / 100;
        second = (number / 10) % 10;
        third = number % 10;
         sum = first * second * third;
         if (sum == 0) {
             continue;
         }
         if (number % sum == 0) {
            cout << number << endl;
        }
    }
    */

}

    
    
   

    
