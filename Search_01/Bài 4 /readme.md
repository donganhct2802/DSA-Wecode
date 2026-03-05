# [Search01.04] 

##  1. Bài tập
<img width="1125" height="847" alt="{03C94FCE-1CB4-41C7-9AE5-88EBC4CAEDAA}" src="https://github.com/user-attachments/assets/4bc1cd4d-c9d7-4325-871f-274f35d7cb1b" />





---
##  2. Template Mẫu

```cpp

#include <iostream>
using namespace std;

void NhapMang(int A[], const int N) {
    for (int i = 0; i < N; i++)
        std::cin >> A[i];
}


// Your code here



int main() {
    int x; cin >> x;
    int n; cin >> n;

    int *a = new int[n];

    for (int i = 0; i < n; i++)
        cin >> a[i];

    cout << std::boolalpha << binary_search(a, n, x);;

    return 0;
}



```
