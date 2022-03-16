# How-to-calculate-the-sequence-of-numbers-S-n-using-the-iterative-method
How to calculate the sequence of numbers S(n) using the iterative method
#include<iostream>
using namespace std;
int sum(int n) {
    int sum = 0;
    for (int i = 0; i <= n; i++)
        sum += i;
    return sum;
}
int main() {
    int n;
    do {
        cout << "Nhap n: ";
        cin >> n;
    } while (n <= 0);
    cout << "Tong cua day so la: " << sum(n)<<endl;
    system("pause");
    return 0;
}
