# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program

```
import re
lis=[] 
items=['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items: 
   if not re.search(r"e",i): 
      lis.append(i) 
print(lis)
```
## Output

![439298870-f2d132bc-1988-4d51-957a-ca53442d39e9](https://github.com/user-attachments/assets/d96913e6-b885-4530-b3cd-dd9424015faf)

## Result

Thus the program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** is executed successfully.
