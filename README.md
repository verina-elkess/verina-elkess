
#include <iostream>
using namespace std;

int main() {
float fahrenheit, celsius;

    char input1;
    double input2;



    cout << "Enter c to convert Fahrenheit to Celsius or f  to convert Celsius to Fahrenheit: \n";
    cin >> input1;


    if (input1 == 'c')
    {
      cout << "Enter your temperature in Fahrenheit: ";
      cin >> input2;
      cout << endl;
      cout << "Your temperature in Celsius is: " << (input2 - 32) * (5.0/9.0) << endl;
    }

  else if (input1 == 'f')
  {
    cout << "Enter your temperature in Celsius: ";
    cin >> input2;
    cout << endl;
    cout << "Your temperature in Fahrenheit is: " << (input2 * 1.8) + (32) << endl;
  }

    return 0;
}

