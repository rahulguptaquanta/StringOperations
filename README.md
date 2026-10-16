# String Operations

This Java console project contains two programs for practicing string methods, loops, and conditional statements.

## Programs

- `PalindromeChecker.java` checks whether the entered text is a palindrome. It ignores spaces, punctuation, and letter case.
- `VowelCounter.java` counts the vowels (`a`, `e`, `i`, `o`, `u`) in the entered text.

## Requirements

- Java Development Kit (JDK) 8 or later

## Compile and run

Open a terminal in the project root.

### Palindrome checker

```bash
javac -d out src/com/internship/strings/PalindromeChecker.java
java -cp out com.internship.strings.PalindromeChecker
```

### Vowel counter

```bash
javac -d out src/com/internship/strings/VowelCounter.java
java -cp out com.internship.strings.VowelCounter
```

## Example

Palindrome checker input: `Never odd or even`

Output:

```text
The string is a palindrome.
```

Vowel counter input: `Hello World`

Output:

```text
Number of vowels: 3
```
