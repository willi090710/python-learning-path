# Conditions

**Date:** Jun 27, 2026

## What I Learned

- `if`, `elif`, and `else` conditions

---

## What is a condition?

- A condition checks whether something is `True` or `False`.

---

## `if`

- The code inside an `if` statement only runs if the condition is `True`.

### Example

```python
name = "Willi"

if name == "Willi":
    print("Hello Willi")
```

### Output

```text
Hello Willi
```

- If the condition is `False`, the code inside the `if` statement will not run.

### Example

```python
age = 15

if age >= 18:
    print("You are old enough.")
```

### Output

```text
# Nothing is printed because the condition is False.
```

---

## `else`

- The code inside `else` runs if the `if` condition is `False`.

### Example

```python
has_ticket = False

if has_ticket:
    print("Welcome!")
else:
    print("You need to buy a ticket first.")
```

### Output

```text
You need to buy a ticket first.
```

---

## `elif`

- `elif` lets you check additional conditions if the previous condition is `False`.

### Example

```python
grade = "B"

if grade == "A":
    print("Very good")
elif grade == "B":
    print("Good")
elif grade == "C":
    print("OK")
else:
    print("You need to study more.")
```

### Output

```text
Good
```

- Python checks each condition from top to bottom until it finds one that is `True`. After that, it skips the remaining conditions.
