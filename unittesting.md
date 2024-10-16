
# 🧪 **Unit Testing** [![Testing Badge](https://img.shields.io/badge/Unit%20Testing-Essential-brightgreen?style=for-the-badge)](https://shields.io)

## What is Unit Testing?

**Unit Testing** is a software testing method where individual components or "units" of a software are tested independently to ensure they work as expected. The main goal is to validate that each piece of the software (usually a function or method) performs its task correctly. Unit testing helps in catching bugs early in the development cycle and ensures that the codebase remains maintainable and reliable.

### 📝 Example Scenario:

Imagine a calculator application where you want to test the addition function. In unit testing, you'd isolate that function and verify whether it correctly returns the sum of two numbers.

---

## 📊 Types of Unit Testing

[![Manual Testing](https://img.shields.io/badge/Manual%20Testing-Involves%20Manual%20Execution-yellow?style=for-the-badge)](https://shields.io)

[![Automated Testing](https://img.shields.io/badge/Automated%20Testing-Coded%20Execution-blue?style=for-the-badge)](https://shields.io)

1. **Manual Unit Testing**: Manually executing test cases to check the functionality of a unit.
2. **Automated Unit Testing**: Writing scripts to automatically test the functionality of a unit using frameworks (e.g., JUnit, pytest).

---

## 🛠️ Unit Testing Techniques

Unit testing can be performed using various techniques to cover different parts of the code:

### 🔍 1. **Structural Techniques**

These focus on testing the internal structure and control flow of a unit.

#### a. **Statement Testing**
**Definition**: Ensures that every line of code is executed at least once.
```python
def is_even(number):
    if number % 2 == 0:
        return True
    else:
        return False

```
- Test Case `1`: `is_even(4)` should return True.
- Test Case `2`: `is_even(3)` should return False.
---
#### b. **Statement Testing**
**Definition**: Tests every condition (e.g., boolean expressions) to ensure that both true and false outcomes are covered.
```python
def check_positive_even(number):
    if number > 0 and number % 2 == 0:
        return True
    else:
        return False
```
- Test Case `1`: `check_positive_even(4)` should return True.
- Test Case `2`: `check_positive_even(-4)` should return False.
- Test Case `3`: `check_positive_even(3)` should return False.

---
#### c. **Branch Testing**
**Definition**: Tests all possible branches in conditional statements.
```python
def calculate_grade(score):
    if score >= 90:
        return 'A'
    elif score >= 80:
        return 'B'
    else:
        return 'C'
```
- Test Case `1`: `calculate_grade(92)` should return 'A'.
- Test Case `2`: `calculate_grade(85)` should return 'B'.
- Test Case `3`: `calculate_grade(75)` should return 'C'.

---

#### d. **Path Testing**
**Definition**: Tests all possible execution paths in a function.
```python
def operation(a, b, op):
    if op == "add":
        return a + b
    elif op == "subtract":
        return a - b
    else:
        return None

```

- Test Case `1`: `operation(2, 3, 'add')` should return `5`.
- Test Case `2`: `operation(5, 2, 'subtract')` should return `3`.
- Test Case `3`: `operation(5, 2, 'multiply')` should return `None`.

---

# 🚀 Unit Testing Methods

Unit testing is conducted using different testing methods. These focus on how the internal logic is verified.

[![Gray Box](https://img.shields.io/badge/Testing%20-White%20Box%20-white?style=for-the-badge)](https://shields.io)

**Tests internal logic, code structure, and behavior.**

**Example:**  
Testing a sorting algorithm by verifying each condition and loop.

---

[![Gray Box](https://img.shields.io/badge/Testing%20-Black%20Box%20-black?style=for-the-badge)](https://shields.io)

**Tests the unit based on inputs and expected outputs without knowing the code structure.**

**Example:**  
Testing an addition function by providing inputs and checking if the output is correct.

---


[![Gray Box](https://img.shields.io/badge/Testing%20-Gray%20Box%20-DAD7CD?style=for-the-badge)](https://shields.io)


**Combines aspects of both white box and black box testing.**

**Example:**  
Testing a web service by knowing partial implementation but primarily testing inputs/outputs.

---

## 📌 Real-Life Example of Unit Testing

Consider a banking application where you have a function that calculates the interest on a savings account:

```python
def calculate_interest(balance, rate):
    return balance * rate
```

### Test Cases:
- Test Case `1`: If the balance is `$1000` and the rate is `0.05`, `calculate_interest(1000, 0.05)` should return `50`.
- Test Case `2`: For a balance of `0`, `calculate_interest(0, 0.05)` should return `0`.
- Test Case `3`: For a negative balance, `calculate_interest(-100, 0.05)` should return `-5`.


### Automated Unit Testing

```python
def test_calculate_interest():
    assert calculate_interest(1000, 0.05) == 50
    assert calculate_interest(0, 0.05) == 0
    assert calculate_interest(-100, 0.05) == -5
```
---
## 🏁 Conclusion

Unit testing is a foundational practice that helps ensure individual components work properly before integrating them into larger systems. Techniques like statement, condition, branch, and path testing, along with methods such as white box and black box testing, enable developers to maintain a reliable codebase.
