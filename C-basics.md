# Task 3 — Markdown Documentation

## 1. Data Types

| Data Type | Description |
| :--- | :--- |
| `int` | Stores whole numbers (integers) without decimals |
| `float` | Stores single-precision floating-point numbers |
| `double` | Stores double-precision floating-point numbers |
| `char` | Stores a single character |
| `bool` | Stores boolean values (`true` or `false`) |
| `void` | Represents the absence of a value |

---

## 2. Format Specifiers

| Format Specifier | Description |
| :--- | :--- |
| `%d` | Signed decimal integer |
| `%u` | Unsigned decimal integer |
| `%o` | Unsigned octal integer |
| `%x` | Unsigned hexadecimal integer (lowercase) |
| `%X` | Unsigned hexadecimal integer (uppercase) |
| `%f` | Floating-point number |
| `%e` | Exponential/scientific notation |
| `%c` | Single character |
| `%s` | String of characters |
| `%ld` | Signed long integer |

---

## 3. Input/Output Functions

* **`scanf()`**: Reads formatted input from standard input.
* **`printf()`**: Prints formatted output to standard output.
* **`getchar()`**: Reads a single character from standard input.
* **`putchar()`**: Writes a single character to standard output.
* **`fgets()`**: Reads a string from standard input safely with a size limit.
* **`puts()`**: Writes a string to standard output followed by a newline.

---

## 4. Escape Sequences

* **`\n`**: Newline
* **`\t`**: Horizontal tab
* **`\\`**: Backslash
* **`\"`**: Double quote
* **`\r`**: Carriage return

---

## 5. Precision

Precision for floating-point output is specified using a period (`.`) followed by a number before the format specifier (e.g., `%.2f`).

* **Example**: `printf("%.2f", 3.14159);` outputs `3.14`.
*
