# [Sort01.02]

##  1. Bài tập
<img width="1131" height="754" alt="{7D7A1E82-2119-4FDF-BD6F-E7A79A332B4B}" src="https://github.com/user-attachments/assets/74cbb1c5-6676-44f1-bd87-c8565fb6413b" />








---
##  2. Template Mẫu

```cpp

#include <iostream>
#define MAXN 100000

void NhapMang(int A[], int &N) {
    std::cin >> N;
    for (int i = 0; i < N; i++)
        std::cin >> A[i];
}
void hoanvi(int &x, int &y){
    int temp=x;
    x=y;
    y=temp;
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

    selection_sort_decending(a, n);

    XuatMang(a, n);

    return 0;
}


```
