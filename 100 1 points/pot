#include <iostream>
#include <cmath>
using namespace std;
int main() {
    int N;

    cin >> N;
    long sum = 0;
    for(int i = 1; i <= N; i++){
        long num;
        cin >> num;

        long power = num % 10;
        long realNum = num / 10;

        long result = 0;
        result += pow(realNum, power);
        sum += result;
    }

    cout << sum << endl;
}