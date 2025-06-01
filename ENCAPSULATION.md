# Exp.No:29  
## Encapsulation

---

### AIM  
To write a Python program to create a class `Student` with the private members `name` and `age`, and add getter and setter methods to initialize and modify the `age` variable.

---

### ALGORITHM

1. **Start the Program.**
2. **Define the `Student` class.**
   - Inside the `Student` class, define the `__init__` method to initialize `name` and the private member `__age`.
3. **Define a getter method** `get_age` to return the value of the private member `__age`.
4. **Define a setter method** `set_age` to set a new value to the private member `__age`.
5. **Create an object `stud`** of the `Student` class with the name 'Jessa' and age 14.
6. **Print the name and the age** of `stud` using the getter method.
7. **Use the setter method** `set_age` to change the age of `stud` to 16.
8. **Print the name and the updated age** of `stud` using the getter method.
9. **End the program.**

---

### PROGRAM

```
Reg no-212223020028
Name-Tharani devi.G
write your code
class Student:
    def __init__(self, name, age):
        self.name = name
        self.age = age
    def get_name(self):
        return self.name
    def set_name(self):
        self.name=n
    def get_age(self):
        return self.age
    def set_age(self,a):
        self.age=a
   
b=Student('Jessa', 14)
print("Name:",b.get_name(),b.get_age())
b.set_age(16)
print("Name:", b.get_name(),b.get_age())




```

### OUTPUT
![image](https://github.com/user-attachments/assets/25f30454-95c7-4025-bc33-34801c519064)


### RESULT
This program for create a class Student with the private members name and age, and add getter and setter methods to initialize and modify the age variable is successfully executed.

