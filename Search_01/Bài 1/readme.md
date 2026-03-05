# [Search01.01] Tìm giá trị X trong mảng

##  1. Bài tập
<img width="1134" height="843" alt="{045CBDA9-212A-4A04-A61A-625D9EAC2195}" src="https://github.com/user-attachments/assets/c5a3736b-68a1-495d-bf84-aed816b0427e" />



---
##  2. Template Mẫu

```cpp
#include <iostream>
using namespace std;

// Your code here


int main() {
    int x; cin >> x;
    int n; cin >> n;

    int *a=new int[n];

    for (int i = 0; i < n; i++)
        cin >> a[i];

    cout << std::boolalpha << binary_search(a, 0, n-1, x);;

    return 0;
}
```

