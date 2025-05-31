##﻿# Favourite-Numbers-CC


---

### 🔍 **Detailed Explanation:**

#### `#include <bits/stdc++.h>`

* A commonly used header in competitive programming that includes almost all standard C++ libraries.

#### `using namespace std;`

* This allows you to use standard names like `cin`, `cout`, `endl`, etc., without needing to prefix them with `std::`.

---

### 👨‍💻 **Main Logic:**

```cpp
int t;
cin >> t;
```

* Reads the number of test cases `t`.

```cpp
while (t--) {
```

* Loops through each test case.

```cpp
    int a;
    cin >> a;
```

* Reads an integer `a` for the current test case.

---

### 🧠 **Decision Logic:**

```cpp
if (a % 2 == 0 && a % 7 == 0) {
    cout << "Alice" << endl;
}
```

* If `a` is divisible by **2** **and** **7** (i.e., divisible by 14), it prints `"Alice"`.

```cpp
else if (a % 2 != 0 && a % 9 == 0) {
    cout << "bob" << endl;
}
```

* If `a` is **odd** and divisible by **9**, it prints `"bob"`.

```cpp
else {
    cout << "Charlie" << endl;
}
```

* If neither of the above conditions are met, it prints `"Charlie"`.

---

### 📌 **Example:**

If input is:

```
3
14
27
8
```

The output will be:

```
Alice    // 14 is divisible by 2 and 7
bob      // 27 is odd and divisible by 9
Charlie  // 8 is even but not divisible by 7 or 9
```

