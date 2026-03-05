# [Search01.08]

##  1. Bài tập
<img width="1133" height="802" alt="image" src="https://github.com/user-attachments/assets/77253ad9-5c7e-45ad-8318-aeee31c8b59d" />



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

    cout << binary_search_last_occurrence(a, n, x);

    return 0;
}



```
