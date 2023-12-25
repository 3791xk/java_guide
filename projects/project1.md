# Variables + Variable Types 
Familiarize yourself with Java's variable types (String, int, double, float, boolean) and how to produce terminal line output.
# Shape Calculator
## Instructions:
Your task is to create an interactive shape calculator. When the program runs, it will first **ask the user their name**, then **one at a time for length, width, height, and radius values**. The length and width are integers, but the radius can be a decimal value. You will then output (using the user's name) the volume and surface area of a rectangular prism (using length, width, and height), cylinder (using radius and height) and a sphere (using radius). You can assume the user will always input valid numbers.

**Hint:** You will need to learn how to take user input in through terminal ([Scanner reccomended](https://www.w3schools.com/java/java_user_input.asp)) as well as round your decimal values to two digits after the decimal point.


## Examples:
### Example of expected program questions without user input or results:
```
What's your name? 
Input a length: 
Input a width: 
Input a height: 
Input a radius: 
```
### Example input/output
```
What's your name? Mary Sue
Input a length: 2
Input a width: 4
Input a height: 6
Input a radius: 1.5
Hi Mary Sue, here are the results of the calculation:
Rectangular Prism (2x4x6):
  Volume: 48
  Surface Area: 88
Cylinder (1.5x6):
  Volume: 42.41
  Surface Area: 70.69
Sphere (1.5):
  Volume: 14.14
  Surface Area: 28.27
```
```
What's your name? John Doe
Input a length: 5
Input a width: 7
Input a height: 3
Input a radius: 8
Hi John Doe, here are the results of the calculation:
Rectangular Prism (5x7x3):
  Volume: 105
  Surface Area: 142
Cylinder (8x3):
  Volume: 603.19
  Surface Area: 552.92
Sphere (8):
  Volume: 2144.66
  Surface Area: 804.25
```
