#include <iostream>
using namespace std;

int main()
{
    int num1, num2;
    double average;
    long long square1, square2;

    cout << "Enter the first integer: ";
    cin >> num1;

    cout << "Enter the second integer: ";
    cin >> num2;

    // 1. Remainder of the first number divided by the second number
    if (num2 != 0)
    {
        cout << "Remainder = " << num1 % num2 << endl;
    }
    else
    {
        cout << "Remainder cannot be calculated because the second number is zero." << endl;
    }

    // 2. Average of both numbers
    average = (static_cast<double>(num1) + num2) / 2.0;
    cout << "Average = " << average << endl;

    // 3. Square of the first number
    square1 = 1LL * num1 * num1;
    cout << "Square of the first number = " << square1 << endl;

    // 4. Square of the second number
    square2 = 1LL * num2 * num2;
    cout << "Square of the second number = " << square2 << endl;

    return 0;
}
