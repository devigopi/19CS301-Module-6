6E EX:overloading operator for adding two objects

Aim:
    Write a Python program for simply using the overloading operator for adding two objects.

Algorithm:
Step 1:Start
Step 2:Define a class, e.g., Sample.
Step 3:Inside the class:
    Create an __init__() method to initialize object attributes.
    Define __add__(self, other) method to overload the + operator.
      Inside this method, add attributes of the current object (self) and the other object (other).
      Return a new object containing the result.
Step 4:Create two objects of the class.
Step 5:Use the + operator to add the two objects (which internally calls __add__).
Step 6:Display the result.
Step 7:End

Program:
```
class priya:
    def __init__(self,a,b,c,d):
        self.a=a
        self.b=b
        self.c=c
        self.d=d
    def __add__(self,other):
        return self.a+other.a,self.b+other.b,self.c+other.b,self.c+other.c,self.d+other.d
ob1=int(input())
ob2=int(input())
ob3=str(input())
ob4=str(input())
print("adding integers :",ob1+ob2)
print("adding strings :",ob3+ob4
```

Output:

![6e](https://github.com/user-attachments/assets/27421bd1-f249-4e3a-afd2-02edcb9e6239)

Result:
    Thus, the given program is implemented and executed successfully .
