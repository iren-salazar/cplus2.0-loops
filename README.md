#C++ loops 
The sum of numbers and prog. will stop if i'll type " 0 "

#include <iostream>

using namespace std;

int main() {
int number;
int sum = 0;
//take input from the user 
cout << " Enter a number: " << endl;
cin >> number;
while (number >= 1) {
//add all positive numbers      
sum += number;
//take input again if the number is positive      
cout << " Enter a number: " << endl;
cin >> number;
}
// display the sum
cout << "\n The sum is " << sum << endl;
return 0;
}
