# Exp.No:25  
## Hierarchical Inheritance

### AIM  
To write a Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor`.

### ALGORITHM

1. **Begin the program.**
2. **Create a class Details** with an `__init__` method to initialize three attributes: `id`, `name`, and `gender`.
3. **Define a method display_details()** to print the values of `id`, `name`, and `gender`.
4. **Create a class Employee** that inherits from the `Details` class. 
   - Add two additional attributes: `company` and `department`.
   - Override the `display_details()` method to print the employee-specific attributes (`company` and `department`) along with the inherited details.
5. **Create a class Doctor** that also inherits from the `Details` class. 
   - Add two additional attributes: `hospital` and `department`.
   - Override the `display_details()` method to print the doctor-specific attributes (`hospital` and `department`) along with the inherited details.
6. **Accept input** for employee and doctor details.
7. **Create objects of Employee and Doctor** using the input.
8. **Call the `display_details()` method** for both objects to print the details.
9. **Terminate the program.**

### PROGRAM
```
Reg.No: 212222060182
Name: Preethika S

class value:
    def get_values(self,a,b):
        self.a=a
        self.b=b
        self.c=a-b
class subtract(value):
    def sub(self):
        print(" subraction value1 : ",a)
        print(" subraction value2 : ",b)
        print("Subracted value :",self.c)
a=int(input()) 
b=int(input()) 
obj=subtract()
obj.get_values(a,b)
obj.sub()
```

### OUTPUT  
<img width="1013" height="307" alt="image" src="https://github.com/user-attachments/assets/0bbe4bed-4812-4757-98e0-80350bdbd1c9" />

### RESULT
Thus , a Python program to Calculate subraction using hierarchical inheritance is executed successfully.
