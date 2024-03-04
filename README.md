//2019.11.22  파보나치
#include <iostream>

using namespace std;

int num(int n) {
	if (n == 1)
		return 0;
	else if (n == 2)
		return 1;
	else
		return num(n - 1) + num(n - 2);
}

int main() {
	int n;
	cout << "몇번째 수:";
	cin >> n;
	cout << num(n) << endl;
	return 0;
}
