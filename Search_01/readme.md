# [Search01.10]

##  1. Bài tập
<img width="1128" height="843" alt="image" src="https://github.com/user-attachments/assets/7164aee9-00da-4f76-99e1-cb8989b35a3b" />



---
##  2. Template Mẫu

```cpp


#include <iostream>
#define MAXN 400000

void NhapMang(int A[], int &N) {
    std::cin >> N;
    for (int i = 0; i < N; i++)
        std::cin >> A[i];
}

int Sentinel_LinearSearch(int A[], int N, int X) {
    int last=A[N-1]; // Lưu lại giá trị cuối danh sách

    A[N-1]=X; // Đặt giá trị X vào cuối danh sách

// Your code here

    return -1;
}


int main() {
    int a[MAXN], n, x;

    std::cin >> x;

    NhapMang(a, n);

    int i = Sentinel_LinearSearch(a, n, x);

    if (i==-1) std::cout << "false";
    else std::cout << "true";

    return 0;
}




```
