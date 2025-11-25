#include <iostream>
using namespace std;

int main() {
    int n;
    cout << "Enter n: ";
    cin >> n;

    double a = 1.0;

    int k = 1;
    while (k <= n) {
        a = k * a + 1.0 / k;
        cout << "a" << k << " = " << a << endl;
        k++;
    }

    return 0;
}
