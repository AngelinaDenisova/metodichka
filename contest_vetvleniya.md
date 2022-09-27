Определить, является ли треугольник со сторонами a, b, c равносторонним.
#include <iostream>
using namespace std;
int main() {
	int a, b, c;
	cin >> a >> b >> c;
	if ((a == b) && (b == c)) {
		cout << "Yes";
	}
	else {
		cout << "No";
	}
	return 0;
}
	
	
Дано целое трехзначное число. Определить, равен ли квадрат этого числа сумме кубов его цифр.
#include <iostream>
using namespace std;

int main() {
	int ch, x, y, z;
	cin >> ch;
	x = ch / 100;
	ch = ch % 100;
	y = ch / 10;
	ch = ch % 10;
	z = ch;
	if (ch * ch == pow(x, 3) + pow(y, 3) + pow(z, 3)) {
		cout << "Yes";
	}
	else {
		cout << "No";
	}
	return 0;

}
