# Python – Βασικές εντολές με αγγλικά ονόματα μεταβλητών

```python
# 1. Εμφάνιση μηνύματος
print("Hello world")

# 2. Εμφάνιση αριθμού
print(123)

# 3. Μεταβλητές
age = 20
height = 1.75
name = "Maria"
is_student = True

print(age)
print(height)
print(name)
print(is_student)

# 4. Αριθμητικές πράξεις
a = 5
b = 3

print(a + b)      # πρόσθεση
print(a - b)      # αφαίρεση
print(a * b)      # πολλαπλασιασμός
print(a / b)      # διαίρεση (float)
print(a // b)     # ακέραιη διαίρεση
print(a % b)      # υπόλοιπο
print(a ** b)     # δύναμη

# 5. Τελεστές σύγκρισης
x = 10
y = 7

print(x == y)
print(x != y)
print(x > y)
print(x < y)
print(x >= y)
print(x <= y)

# 6. Λογικοί τελεστές
is_adult = age >= 18
has_ticket = True

print(is_adult and has_ticket)
print(is_adult or has_ticket)
print(not is_adult)

# 7. if - elif - else
grade = 15

if grade >= 18:
    print("Excellent")
elif grade >= 10:
    print("Pass")
else:
    print("Fail")

# 8. Βρόχος for
for i in range(1, 6):
    print(i)

# 9. Βρόχος while
counter = 1
while counter <= 5:
    print(counter)
    counter += 1

# 10. Λίστα
numbers =[1]
print(numbers)
print(numbers)
numbers.append(40)
print(numbers)

# 11. Συνάρτηση
def add(a, b):
    return a + b

result = add(5, 7)
print(result)

# 12. Είσοδος από το πληκτρολόγιο (προαιρετικά)
# name = input("Give your name: ")
# print("Hello", name)
