# [Sort01.10]

##  1. Bài tập
<img width="1127" height="822" alt="{1AF049D0-A543-4F47-A43E-79F75D7DD2EA}" src="https://github.com/user-attachments/assets/efc43ad7-6e61-48ef-97f8-2829b358d731" />


---
##  2. Template Mẫu

```cpp
#include<iostream>

void XuatMang(int A[], int N) {
    for (int i = 0; i < N; i++)
        std::cout << A[i] << '\t';
    std::cout << std::endl;
}

// Your code here


int main() {
    int a[MAXN], n;
    NhapMang(a, n);
    SapXepSoDuongGiamAmTangVa0(a, n);
    XuatMang(a, n);
    return 0;
}


```
