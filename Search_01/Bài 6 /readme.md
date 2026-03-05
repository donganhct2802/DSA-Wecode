# [Search01.06]

##  1. Bài tập
<img width="1134" height="811" alt="image" src="https://github.com/user-attachments/assets/18b2c061-5bf4-433e-bdbc-955f043da65b" />



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

    cout << binary_search_first_occurrence(a, n, x);

    return 0;
}

```
