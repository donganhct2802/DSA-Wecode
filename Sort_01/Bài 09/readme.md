# [Sort01.09]

##  1. Bài tập
<img width="1119" height="831" alt="{B553B5A6-B1B7-4F35-8216-7FEBFD323679}" src="https://github.com/user-attachments/assets/497c00dc-a29a-4e99-bf13-bae6c731aec9" />







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
    n=Input();
    NhapMang(a, n);
    SapXepSoChanGiamDan(a, n);
    XuatMang(a, n);
    return 0;
}


```
