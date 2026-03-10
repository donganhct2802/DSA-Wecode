# [Sort01.01]

##  1. Bài tập
<img width="1109" height="851" alt="{CDCB563D-A9C4-4562-8701-B80AF1F62ECF}" src="https://github.com/user-attachments/assets/009e87e4-3837-4285-a2e9-82db4cf45071" />







---
##  2. Template Mẫu

```cpp

// Your code here


int main() {
    int a[MAXN], n;

    std::cin >> n;

    NhapMang(a, n);

    selection_sort_ascending(a, n);

    std::cout << std::boolalpha << is_ascending(a, n);

    return 0;
}

```
