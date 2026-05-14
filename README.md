# Test
Репозиторий для проб 

def add(a, b):
    return a + b

def subtract(a, b):
    return a - b

def multiply(a, b):
    return a * b

def divide(a, b):
    if b == 0:
        raise ValueError("Cannot divide by zero")
    return a / b

def test_add():
    assert add(2, 3) == 5
    assert add(-1, 1) == 0
    print("✅ test_add passed!")

def test_subtract():
    assert subtract(5, 3) == 2
    assert subtract(10, 7) == 3
    print("✅ test_subtract passed!")

def test_multiply():
    assert multiply(4, 5) == 20
    assert multiply(-2, 3) == -6
    print("✅ test_multiply passed!")

def test_divide():
    assert divide(10, 2) == 5
    assert divide(9, 3) == 3
    print("✅ test_divide passed!")

def test_multiplication_by_zero():
    assert multiply(5, 0) == 0
    assert multiply(100, 0) == 0
    print("✅ test_multiplication_by_zero passed!")

