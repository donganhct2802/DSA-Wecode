# [Sort01.03]

##  1. Bài tập
<img width="1119" height="741" alt="{73622C97-BB14-4368-82C7-57AD9200F8FA}" src="https://github.com/user-attachments/assets/bfd39426-bbfa-42e7-bada-917c602bd8d0" />








---
##  2. Template Mẫu

```cpp

#include <iostream>
#define MAXN 30000

void NhapMang(int A[], int &N) {
    std::cin >> N;
    for (int i = 0; i < N; i++)
        std::cin >> A[i];
}


// Your code here

void XuatMang(int A[], const int &N) {
    std::cout << N << std::endl;
    for (int i = 0; i < N; i++)
        std::cout << A[i] << " ";
}

int main() {
    int a[MAXN], n;

    NhapMang(a, n);

    insertionSort_sort_decending(a, n);

    XuatMang(a, n);

    return 0;
}


```
