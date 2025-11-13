// Write a C program to print arithmetic operations (+, -, *, /) using switch

#include <iostream>
using namespace std;

int main()
{
    char op;
    double num1, num2;

    cout << "Enter operator (+, -, *, /): ";
    cin >> op;

    cout << "Enter two numbers: ";
    cin >> num1 >> num2;

    switch (op)
    {
        case '+':
            cout << num1 << " + " << num2 << " = " << num1 + num2;
            break;

        case '-':
            cout << num1 << " - " << num2 << " = " << num1 - num2;
            break;

        case '*':
            cout << num1 << " * " << num2 << " = " << num1 * num2;
            break;

        case '/':
            if (num2 != 0)
                cout << num1 << " / " << num2 << " = " << num1 / num2;
            else
                cout << "Error! Division by zero.";
            break;

        default:
            cout << "Invalid operator!";
            break;
    }

    return 0;
}
output
Enter operator (+, -, *, /): +
Enter two numbers: 8 9
8 + 9 = 17

Enter operator (+, -, *, /): -
Enter two numbers: 45 11
45 - 11 = 34

Enter operator (+, -, *, /): *
Enter two numbers: 9 6
9 * 6 = 54

Enter operator (+, -, *, /): /
Enter two numbers: 15 3
15 / 3 = 5
