# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
      class Rectangle:
         
          def __init__(self, length, breadth):
              self.__length = length      # Private variable
              self.__breadth = breadth    # Private variable
              self.__display_values()     # Accessing within class
      
          
          def __display_values(self):
              print("Length:", self.__length)
              print("Breadth:", self.__breadth)
      
      rect = Rectangle(10, 5)

## Output
![Screenshot 2025-05-20 052210](https://github.com/user-attachments/assets/2c68e2fe-13cb-4f2d-805c-7c6c409129c2)


## Result
 Thus, the program is verified successfully.
