# 🌀 Palindrome Checker (Python)

This is a simple Python program that checks whether a given word or phrase is a palindrome.

## 💡 What is a Palindrome?

A palindrome is a word, number, phrase, or sequence that reads the same backward as forward, such as:

- `madam`
- `racecar`
- `level`

## 🧠 How It Works

The program:
1. Accepts a user input.
2. Reverses the input.
3. Compares it to the original.
4. Outputs whether it is a palindrome or not.

## 📄 Example Code

```python
text = input("Enter a word: ")
if text == text[::-1]:
    print("Palindrome")
else:
    print("Not a Palindrome")

