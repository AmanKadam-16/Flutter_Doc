# Day 1 
# Data Types in Flutter

In Flutter, data types are fundamental building blocks that define the type of data a variable can hold. Flutter uses Dart as its programming language, which is strongly typed. Below are the primary data types in Dart that you will encounter when developing Flutter applications.

## 1. Numbers
Dart supports two types of numeric values:

### a. `int`
- Represents whole numbers.
- Example:
  ```dart
  int age = 25;
  ```

### b. `double`
- Represents floating-point numbers.
- Example:
  ```dart
  double price = 19.99;
  ```

### c. `num`
- Can hold both `int` and `double` types.
- Example:
  ```dart
  num temperature = 98.6;
  temperature = 37; // Valid
  ```

## 2. Strings
- Used to represent text.
- Enclosed in either single or double quotes.
- Example:
  ```dart
  String name = 'Flutter';
  String greeting = "Hello, World!";
  ```

### String Interpolation
- Use `$variable` or `${expression}` to embed variables or expressions inside strings.
- Example:
  ```dart
  String name = 'Flutter';
  String message = 'Welcome to $name!';
  ```

## 3. Booleans
- Represents true/false values.
- Example:
  ```dart
  bool isLoggedIn = true;
  bool hasAccess = false;
  ```

## 4. Lists
- Ordered collection of items.
- Similar to arrays in other languages.
- Example:
  ```dart
  List<int> numbers = [1, 2, 3, 4, 5];
  ```

### Properties of Lists
- Can be fixed-length or growable.
- Example:
  ```dart
  List<String> names = ['Alice', 'Bob'];
  names.add('Charlie');
  ```

## 5. Maps
- Key-value pair collections.
- Example:
  ```dart
  Map<String, String> capitals = {
    'India': 'New Delhi',
    'USA': 'Washington, D.C.',
  };
  ```

### Accessing Map Values
- Use keys to access values.
- Example:
  ```dart
  print(capitals['India']); // Outputs: New Delhi
  ```

## 6. Sets
- Unordered collection of unique items.
- Example:
  ```dart
  Set<int> uniqueNumbers = {1, 2, 3, 3};
  print(uniqueNumbers); // Outputs: {1, 2, 3}
  ```

## 7. Runes
- Represent Unicode characters in Dart.
- Example:
  ```dart
  Runes heart = Runes('❤');
  print(String.fromCharCodes(heart));
  ```

## 8. Symbols
- Used to refer to identifiers in a program.
- Rarely used.
- Example:
  ```dart
  Symbol symbol = #mySymbol;
  ```

## 9. Dynamic
- Can hold any type of data.
- Example:
  ```dart
  dynamic variable = 10;
  variable = 'Hello'; // Valid
  ```

## 10. Null Safety
- Dart ensures variables are non-nullable by default.
- Use `?` to make a variable nullable.
- Example:
  ```dart
  int? age;
  age = null; // Valid
  ```

## Conclusion
Understanding and using data types efficiently is crucial for developing robust and efficient Flutter applications. Dart’s type system is designed to help you write clear and error-free code.

