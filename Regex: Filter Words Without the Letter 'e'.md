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
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
z=[]
s=set("e")
for i in items:
    if not s &set(i):
        z.append(i)
print(z)        
## Output
<img width="1168" height="196" alt="image" src="https://github.com/user-attachments/assets/a453a4db-aa07-4e2b-a09b-fc60501b1125" />

## Result
Thus the Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)** was successfully completed
