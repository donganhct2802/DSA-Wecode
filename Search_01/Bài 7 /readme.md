# [Search01.07]

##  1. Bài tập
<img width="1115" height="836" alt="image" src="https://github.com/user-attachments/assets/cc4e608f-d3e9-4c3a-8179-63f75628445a" />



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

    cout << binary_search_greatestLesser_last_occurrence(a, n, x);

    return 0;
}


```
