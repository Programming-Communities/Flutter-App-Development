

---

### **Lac:00 - Installation Android Studio, IDX Google, DartPad Flutter**
**Video Link:** [Lac:00](https://www.youtube.com/live/haqBjxJUJC8?si=I9msbvXxo9LfZqp3)

**Topics Covered:**
1. **Android Studio Installation**: Step-by-step guide to installing Android Studio for Dart and Flutter development.
2. **IDX Google**: Introduction to Google's IDX platform for coding.
3. **DartPad**: Overview of DartPad, an online Dart programming environment.
4. **Flutter Setup**: Basic setup for Flutter development.

**Explanation:**
- This session is focused on setting up the development environment for Dart and Flutter.
- Android Studio is the primary IDE for Flutter development, and DartPad is a quick way to test Dart code without any setup.
- The video walks through the installation process and ensures that all tools are correctly configured.

---

### **Lac:01 - Intro Dart Programming Language & Variable, Integer, String, Bool**
**Video Link:** [Lac:01](https://www.youtube.com/live/meQLxiNi5nY?si=s-to7sBWHJlZtOkl)

**Topics Covered:**
1. **Introduction to Dart**: What is Dart? Why use Dart?
2. **Variables**: Declaring and using variables in Dart.
3. **Data Types**: `int`, `String`, `bool`, and `dynamic`.
4. **Code Examples**: Basic Dart programs to demonstrate variables and data types.

**Code Example:**
```dart
void main() {
  // Integer
  int age = 25;
  print("Age: $age");

  // String
  String name = "Jahanzab";
  print("Name: $name");

  // Boolean
  bool isStudent = true;
  print("Is Student: $isStudent");

  // Dynamic
  dynamic dynamicValue = "Hello";
  print("Dynamic Value: $dynamicValue");
  dynamicValue = 100;
  print("Updated Dynamic Value: $dynamicValue");
}
```

**Explanation:**
- Dart is a client-optimized language for fast apps on any platform.
- Variables are used to store data, and Dart supports strong typing with `int`, `String`, `bool`, etc.
- The `dynamic` type allows a variable to hold any type of data.

---

### **Lac:02 - Dart Programming Language & Variables and Datatypes**
**Video Link:** [Lac:02](https://www.youtube.com/live/UjCWp7E15mA?si=LSxBtBLZ57mQxHr-)

**Topics Covered:**
1. **Review of Variables**: Recap of `int`, `String`, `bool`, and `dynamic`.
2. **Constants**: `final` and `const` in Dart.
3. **Type Inference**: How Dart infers data types.

**Code Example:**
```dart
void main() {
  // Final (runtime constant)
  final int salary = 50000;
  print("Salary: $salary");

  // Const (compile-time constant)
  const double pi = 3.14;
  print("PI: $pi");

  // Type Inference
  var city = "Lahore"; // Dart infers city as String
  print("City: $city");
}
```

**Explanation:**
- `final` is used for variables that are set once at runtime.
- `const` is used for compile-time constants.
- Dart can infer the type of a variable using the `var` keyword.

---

### **Lac:03 - Variables and Datatypes**
**Video Link:** [Lac:03](https://www.youtube.com/live/AnGBjZvJgAI?si=xvKZasoB8ZWe3ibZ)

**Topics Covered:**
1. **Numbers**: `int` and `double`.
2. **Strings**: Concatenation and interpolation.
3. **Booleans**: Logical operations.

**Code Example:**
```dart
void main() {
  // Numbers
  int a = 10;
  double b = 20.5;
  print("Sum: ${a + b}");

  // Strings
  String firstName = "Jahanzab";
  String lastName = "Naseer";
  print("Full Name: $firstName $lastName");

  // Booleans
  bool isRaining = true;
  bool isSunny = false;
  print("Is it raining? $isRaining");
  print("Is it sunny? $isSunny");
}
```

**Explanation:**
- Dart supports both integers (`int`) and floating-point numbers (`double`).
- Strings can be concatenated using the `+` operator or interpolated using `$`.

---

### **Lac:04 - String Functions and Operators**
**Video Link:** [Lac:04](https://www.youtube.com/live/jE2jMYKLPVo?si=XbJHtUrp649jvm65)

**Topics Covered:**
1. **String Functions**: `length`, `toUpperCase()`, `toLowerCase()`, `trim()`, `substring()`, etc.
2. **String Operators**: `+`, `==`, `[]`.

**Code Example:**
```dart
void main() {
  String text = "  Dart Programming  ";

  print("Length: ${text.length}");
  print("Uppercase: ${text.toUpperCase()}");
  print("Lowercase: ${text.toLowerCase()}");
  print("Trimmed: ${text.trim()}");
  print("Substring: ${text.substring(2, 6)}");
  print("Character at index 5: ${text[5]}");
}
```

**Explanation:**
- Dart provides various built-in functions to manipulate strings.
- Strings are immutable, so functions like `toUpperCase()` return a new string.

---

### **Lac:05 - Practice Task and if-else Condition**
**Video Link:** [Lac:05](https://youtu.be/m3Mgsbn0s_8?si=rAmu7o-Z_57WFucv)

**Topics Covered:**
1. **If-Else**: Conditional statements in Dart.
2. **Practice Task**: Write a program to check if a number is even or odd.

**Code Example:**
```dart
void main() {
  int number = 7;

  if (number % 2 == 0) {
    print("$number is even.");
  } else {
    print("$number is odd.");
  }
}
```

**Explanation:**
- The `if-else` statement is used for decision-making in Dart.
- The modulus operator `%` is used to check if a number is even or odd.

---

### **Lac:06 - Nested If-Else**
**Video Link:** [Lac:06](https://www.youtube.com/live/JCPasBBMOOQ?si=M147s73CYmCflE0D)

**Topics Covered:**
1. **Nested If-Else**: Using if-else inside another if-else.
2. **Practice Task**: Write a program to find the largest of three numbers.

**Code Example:**
```dart
void main() {
  int a = 10, b = 20, c = 15;

  if (a > b) {
    if (a > c) {
      print("$a is the largest.");
    } else {
      print("$c is the largest.");
    }
  } else {
    if (b > c) {
      print("$b is the largest.");
    } else {
      print("$c is the largest.");
    }
  }
}
```

**Explanation:**
- Nested if-else allows for more complex decision-making.
- The program compares three numbers and prints the largest one.

---

😊