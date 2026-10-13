

/*
Program Title: Sum of First 50 Natural Numbers
Name: ZAINAB FATIMA
Registration Number: L1S26BSCS0047
Assignment: 01
*/

#include <iostream>
using namespace std;

int main() {
    int sum = 0;

    for (int i = 1; i <= 50; i++) {
        sum += i;
    }

    cout << "Sum of first 50 natural numbers (loop): "
         << sum << endl;

    return 0;
}
