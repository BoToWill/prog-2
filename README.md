#include <iostream>
#include <string>
using namespace std;

int main()
{
	for (int counter = 1; counter <= 10; counter++) {
		cout << " " << counter;

	}cout << "   ";

	int i = 11;
	while (i <= 20){
		cout << " " << i;
		i++;

	}cout << "   ";

	int a = 21;
	do {
		cout << " " << a;
		a++;

	} while (a <= 30);

	cin.get();
	return 0;
}
