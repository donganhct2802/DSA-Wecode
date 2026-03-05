# [Search01.09]

##  1. Bài tập
<img width="1130" height="914" alt="image" src="https://github.com/user-attachments/assets/b8966257-a2ab-4c7e-a170-e80d67fb70a0" />


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

    cout << binary_search_leastGreater_firstOccurrence(a, n, x);

    return 0;
}


```
