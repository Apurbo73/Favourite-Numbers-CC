### Favourite Numbers CC:


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
This C++ program processes multiple test cases, where each test case involves reading an integer and determining a name to print based on specific conditions. If the number is divisible by both 2 and 7, it prints "Alice". If the number is odd (not divisible by 2) and divisible by 9, it prints "bob". In all other cases, it prints "Charlie".

The logic is implemented using a while loop to process each test case, and simple if-else conditions to check the number's properties. The output helps categorize numbers based on their divisibility by 2, 7, and 9 into three named categories for clarity or gameplay logic
