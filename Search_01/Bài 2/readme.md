# [Search01.02] Tìm giá trị X trong mảng TĂNG DẦN

##  1. Bài tập
<img width="1140" height="849" alt="{96998927-1C75-4DF1-AB5B-F36D09E9CADE}" src="https://github.com/user-attachments/assets/71486ea4-8a70-4942-9ca9-7c9545b18604" />



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
