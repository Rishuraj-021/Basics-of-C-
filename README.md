# Experiment-1
Aim:To Write Hello World and Calculator program

Theory: 1.The "Hello World" program is a simple program used to display a message on the screen.
It helps beginners understand:
Basic structure of a C++ program
Use of #include, main() function, and cout for output.

2.A Calculator program performs arithmetic operations such as addition, subtraction, multiplication, and division.
It is used to understand:
User input using cin
Variables and data types
Arithmetic operators
Output using cout

CODE: 1. #include <iostream> 
using namespace std;

int main() {
    cout << "Hello World";  
    return 0;               
}
Output: PS C:\Users\Rishu Raj\New folder\c programme> cd "c:\Users\Rishu Raj\New folder\c programme\" ; if ($?) { g++ a.cpp -o a } ; if ($?) { .\a }
Hello World

2. #include <iostream>
using namespace std;

int main() {
    float a, b;
    
    cout << "Enter two numbers: ";
    cin >> a >> b;

    cout << "Sum = " << a + b << endl;
    cout << "Difference = " << a - b << endl;
    cout << "Product = " << a * b << endl;
    cout << "Quotient = " << a / b << endl;

    return 0;
}
Output: PS C:\Users\Rishu Raj\New folder\c programme> cd "c:\Users\Rishu Raj\New folder\c programme\" ; if ($?) { g++ a.cpp -o a } ; if ($?) { .\a }
Enter two numbers: 2
4
Sum = 6
Difference = -2
Product = 8
Quotient = 0.5
