# Lab-1: This program will read the base and height of a triangle, calculate the area, and print out the base, height, and area of a triangle.

#include <iostream>

using namespace std;

int main()
{
	double base, height, area;

	cout << "Enter value for triangle base: ";
	cin >> base;
	cout << "Enter value for triangle height: ";
	cin >> height;
	cout << endl;

	area = .5 * (base * height);

	cout << "Triangle base: " << base << endl;
	cout << "Triangle height: " << height << endl;
	cout << "Triangle area:  " << area << endl;
	cout << endl;

	system("PAUSE");
	return 0;
}
