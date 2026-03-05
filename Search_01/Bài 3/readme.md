# [Search01.03] Em lười viết title rồi

##  1. Bài tập
<img width="1128" height="923" alt="image" src="https://github.com/user-attachments/assets/8fbe2723-c0e1-4cc3-8ac3-7c845d22ca6c" />




---
##  2. Template Mẫu

```cpp

#include <iostream>
using namespace std;
#define MAXN 400000

void NhapMang(int A[], const int N) {
    for (int i = 0; i < N; i++)
        std::cin >> A[i];
}


// Your code here


int main() {
    int x, n, a[MAXN];

    cin >> x;
    cin >> n;
    NhapMang(a, n);

    cout << boolalpha << binary_search(a, 0, n-1, x);

    return 0;
}

```
