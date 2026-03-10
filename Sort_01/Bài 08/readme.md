# [Sort01.08]

##  1. Bài tập
<img width="1111" height="829" alt="{C5462ECB-B731-4897-BE9E-94687E5CC2B6}" src="https://github.com/user-attachments/assets/12ec74af-5ff8-444c-a5c8-86f9cb7b1203" />







---
##  2. Template Mẫu

```cpp

// Your code here

void XuatMang(int A[], int N) {
    for (int i = 0; i < N; i++)
        std::cout << A[i] << '\t';
}
int main() {
    int a[MAXN], n;
    NhapMang(a, n);
    SapXepSoAmTangDan(a, n);
    XuatMang(a, n);
    return 0;
}


```
