# Assignments-
Assignments 
#include <iostream>
using namespace std;

int main() {
    const int SIZE = 10;
    int arr[SIZE]; // static array of size 10

    cout << "Enter 10 integers:" << endl;
    for (int i = 0; i < SIZE; ++i) {
        cin >> arr[i];
    }

    cout << "The values you entered are:" << endl;
    for (int i = 0; i < SIZE; ++i) {
        cout << arr[i] << " ";
    }
    cout << endl;

    return 0;
}

