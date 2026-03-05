# [Search01.05]

##  1. Bài tập
<img width="1124" height="846" alt="{722F9E0A-E4B2-4A94-926F-939410CA841F}" src="https://github.com/user-attachments/assets/248cf60b-a762-490b-b31a-0fcd3d4ac085" />


---
##  2. Template Mẫu

```cpp


#include <iostream>
using namespace std;


// Your code here



int main() {
    int x; cin >> x;
    int n; cin >> n;

    int *a = new int[n];

    for (int i = 0; i < n; i++)
        cin >> a[i];

    cout << std::boolalpha << binary_search(a, 0, n-1, x);

    return 0;
}


```
