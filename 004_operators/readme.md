# Python Arithmetic & Assignment Operators (README)

A concise, beginner‑friendly reference for Python’s **Arithmetic** and **Assignment** operators, with fresh, original examples you can copy‑paste. All code samples are original. Written for absolute beginners.

---

## Arithmetic Operators

Arithmetic operators work with numeric values to perform common math operations.

| Operator | Name           | Example  | Result (given a = 12, b = 5) |
| -------- | -------------- | -------- | ---------------------------- |
| `+`      | Addition       | `a + b`  | `17`                         |
| `-`      | Subtraction    | `a - b`  | `7`                          |
| `*`      | Multiplication | `a * b`  | `60`                         |
| `/`      | Division       | `a / b`  | `2.4`                        |
| `%`      | Modulus        | `a % b`  | `2`                          |
| `**`     | Exponentiation | `a ** b` | `248832`                     |
| `//`     | Floor Division | `a // b` | `2`                          |

### Arithmetic: mini‑examples

```python
a, b = 12, 5
print(a + b)   # 17
print(a - b)   # 7
print(a * b)   # 60
print(a / b)   # 2.4
print(a % b)   # 2 (remainder of 12 / 5)
print(a ** b)  # 248832 (12 raised to power 5)
print(a // b)  # 2 (floor division)
```

---

## Assignment Operators

Assignment operators set or update a variable’s value. The table below shows each operator, a plain‑English name, and its long form.

| Operator         | Name                    | Example              | Same As                 |
| ---------------- | ----------------------- | -------------------- | ----------------------- |
| `=`              | Simple assignment       | `x = 20`             | `x = 20`                |
| `+=`             | Add and assign          | `x += 4`             | `x = x + 4`             |
| `-=`             | Subtract and assign     | `x -= 6`             | `x = x - 6`             |
| `*=`             | Multiply and assign     | `x *= 3`             | `x = x * 3`             |
| `/=`             | Divide and assign       | `x /= 2`             | `x = x / 2`             |
| `%=`             | Modulus and assign      | `x %= 7`             | `x = x % 7`             |
| `//=`            | Floor‑divide and assign | `x //= 5`            | `x = x // 5`            |
| `**=`            | Exponentiate and assign | `x **= 2`            | `x = x ** 2`            |
| `&=`             | Bitwise AND and assign  | `x &= 1`             | `x = x & 1`             |
| <code>\|=</code> | Bitwise OR and assign   | <code>x \|= 8</code> | <code>x = x \| 8</code> |
| `^=`             | Bitwise XOR and assign  | `x ^= 3`             | `x = x ^ 3`             |
| `>>=`            | Right shift and assign  | `x >>= 2`            | `x = x >> 2`            |
| `<<=`            | Left shift and assign   | `x <<= 2`            | `x = x << 2`            |

### Assignment: mini‑examples

```python
x = 20        # start
x += 4        # 24
x -= 6        # 18
x *= 3        # 54
x /= 2        # 27.0
x //= 5       # 5
x %= 4        # 1
x **= 3       # 1 (1 to the power of 3)

# Bitwise compound assignments
x = 9         # 0b1001
x &= 5        # 0b1001 & 0b0101 = 0b0001 -> 1
x |= 2        # 0b0001 | 0b0010 = 0b0011 -> 3
x ^= 7        # 0b0011 ^ 0b0111 = 0b0100 -> 4
x <<= 1       # 0b0100 << 1 = 0b1000 -> 8
x >>= 2       # 0b1000 >> 2 = 0b0010 -> 2
print(x)
```

---

## Beginner Tips

* Use `/` for true division (returns a float); use `//` for floor division.
* After `/=`, your number may become a float. Use `//=` to keep it integer‑like.
* Bitwise operators (`&`, `|`, `^`, `<<`, `>>`) work on the **binary** form of integers.

---
### <Center> Codemiax By Yash Patel </Center>