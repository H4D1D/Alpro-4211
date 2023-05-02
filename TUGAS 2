# Alpro-4211
#include <iostream>
using namespace std;

// Rumus max
int max(int a, int b) {
    if (a > b) {
        return a;
    } else {
        return b;
    }
}

// Rumus min
int min(int a, int b) {
    if (a < b) {
        return a;
    } else {
        return b;
    }
}

// Rumus maxarr
int maxarr(int arr[], int n) {
    int max = arr[0];

    for (int i = 1; i < n; i++) {
        if (arr[i] > max) {
            max = arr[i];
        }
    }

    return max;
}

// Rumus minarr
int minarr(int arr[], int n) {
    int min = arr[0];

    for (int i = 1; i < n; i++) {
        if (arr[i] < min) {
            min = arr[i];
        }
    }

    return min;
}

// Rumus isEven
bool isEven(int num) {
    if (num % 2 == 0) {
        return true;
    } else {
        return false;
    }
}

// Rumus isOdd
bool isOdd(int num) {
    if (num % 2 != 0) {
        return true;
    } else {
        return false;
    }
}

// Rumus isFactor
bool isFactor(int factor, int num) {
    if (num % factor == 0) {
        return true;
    } else {
        return false;
    }
}

// Rumus sumEven
int sumEven(int start, int end) {
    int sum = 0;

    for (int i = start; i <= end; i++) {
        if (i % 2 == 0) {
            sum += i;
        }
    }

    return sum;
}

// Rumus sumOdd
int sumOdd(int start, int end) {
    int sum = 0;

    for (int i = start; i <= end; i++) {
        if (i % 2 != 0) {
            sum += i;
        }
    }

    return sum;
}

int main() {
    // Hasil  Mencari Max
    int num1, num2;

    cout << "Masukkan bilangan pertama: ";
    cin >> num1;

    cout << "Masukkan bilangan kedua: ";
    cin >> num2;

    int result = max(num1, num2);

    cout << "Bilangan terbesar adalah: " << result << endl;
   
   // Hasil Mencari min
    int Result = min(num1, num2);

    cout << "Bilangan terkecil adalah: " << Result << endl;
    
    
    //Hasil Mencari Maxarr
    int n;

    cout << "Masukkan jumlah bilangan dalam array: ";
    cin >> n;

    int arr[n];

    for (int i = 0; i < n; i++) {
        cout << "Masukkan bilangan ke-" << i+1 << ": ";
        cin >> arr[i];
    }

    int maximun = maxarr(arr, n);

    cout << "Bilangan terbesar adalah: " << maximun << endl;
    
    // Hasil Mencari minarr
    int minimum = minarr(arr, n);

    cout << "Bilangan terkecil adalah: " << minimum << endl;
    
    // Hasil Mencari isEven
    int num;

    cout << "Masukkan bilangan: ";
    cin >> num;

    if (isEven(num)) {
        cout << "Bilangan " << num << " adalah bilangan genap" << endl;
    } else {
        cout << "Bilangan " << num << " bukan bilangan genap" << endl;
    }
    
    // Hasil Mencari isOdd
    if (isOdd(num)) {
        cout << "Bilangan " << num << " adalah bilangan ganjil" << endl;
    } else {
        cout << "Bilangan " << num << " bukan bilangan ganjil" << endl;
    }

    // Hasil Mencari isfactor
    int factor, Num;

    cout << "Masukkan bilangan faktor: ";
    cin >> factor;

    cout << "Masukkan bilangan: ";
    cin >> Num;

    if (isFactor(factor, Num)) {
        cout << factor << " adalah faktor dari " << Num << endl;
    } else {
        cout << factor << " bukan faktor dari " << Num << endl;
    }
    
    // Hasil Mencari sumEven
    int start, end;

    cout << "Masukkan bilangan awal: ";
    cin >> start;

    cout << "Masukkan bilangan akhir: ";
    cin >> end;

    int evenSum = sumEven(start, end);

    cout << "Jumlah bilangan genap antara " << start << " dan " << end << " adalah " << evenSum << endl;

    // Hasil Mencari sumOdd
     int oddSum = sumOdd(start, end);

    cout << "Jumlah bilangan ganjil antara " << start << " dan " << end << " adalah " << oddSum << endl;

    return 0;
}
