# Functions in C++ – Print Name Program

A beginner-friendly C++ program demonstrating the use of functions with parameters.

This project takes user input and prints personalized greeting messages using a custom function.

---

## 📌 Features

* Demonstrates function creation and function calls
* Uses string parameters in functions
* Accepts user input
* Prints personalized greetings
* Beginner-friendly and easy to understand

---

## 🛠️ Technologies Used

* C++
* Standard Input/Output (`iostream`)
* String handling

---

## 📂 Program Logic

The program:

1. Defines a function named `printName()`
2. Accepts a string parameter (`name`)
3. Prints:

   * `"Hey"` followed by the user's name
4. Takes two names as input from the user
5. Calls the function separately for both names

---

## 📸 Screenshot

<img width="1330" height="592" alt="Screenshot 2026-06-13 100044" src="https://github.com/user-attachments/assets/195e0998-49b4-45c1-bc73-9dd86631fcd6" />

Example folder structure:

```txt id="v9q0ld"
project-folder/
│
├── main.cpp
├── README.md
└── screenshots/
    └── output.png
```

---

## 💻 Source Code

```cpp id="4mz0fk"
#include<iostream>
using namespace std;

void printName(string name) {
    cout << "Hey " << name << endl;
}

int main() {

    string name;
    cin >> name;

    printName(name);

    cout << endl;

    string name2;
    cin >> name2;

    printName(name2);

    return 0;
}
```

---

## ▶️ How to Run

1. Compile the program:

```bash id="y8jd3m"
g++ main.cpp -o main
```

2. Run the executable:

```bash id="j2p7ke"
./main
```

3. Enter two names when prompted.

---

## 📸 Example Output

```txt id="r2f7ah"
Rishab
Hey Rishab

Rahul
Hey Rahul
```

---

## 📖 Learning Concepts

This project helps beginners understand:

* Functions in C++
* Function parameters
* Function calls
* String input handling
* Reusability of code
* Modular programming

---

## 🔍 Function Used

```cpp id="1vwk7p"
void printName(string name)
```

### Explanation

* `void` → Function does not return any value
* `printName` → Function name
* `string name` → Parameter passed into the function

---

## 👨‍💻 Author

Developed as a beginner-friendly C++ practice project for learning functions and modular programming.
