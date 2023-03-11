//Name: Aldrich Acol Fernandez
//"Facta, non verba."
//Date: 2023
//ICT Basic CPP Calculator

#include <iostream>
using namespace std;

int main() {

char op;
float num1, num2;

cout << "Enter operator/operation: +, -, *, /: ";
cin >> op;

cout << "Enter two operands: ";
cin >> num1 >> num2;

switch(op) {

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
cout << num1 << " / " << num2 << " = " << num1 / num2;
break;

default:
// If the operator is other than +, -, * or /, error/invalid message output is shown
cout << "Error! the said operation is not correct";
break;
}

return 0;
}
