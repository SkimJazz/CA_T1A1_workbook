# T1A1-Workbook

---

## Q1: **Identify** and **explain** common and important components and concepts of web development markup languages.



### 💲 __Solution__


The first thing you see when visiting a particular website is a web page or document. These web pages contain markup languages such as Hypertext Markup Language (HTML). A website designer or front-end developer will use HTML to structure and describe the content within these web pages.
 
An essential concept for markup languages such as HTML is that the nesting of HTML Elements defines the structure of an HTML document to form a hierarchy.
 
An HTML Element structure includes a "Start tag", a "Tag Name", and an "Attribute Name" with an "Attribute Value" of the "Element Content" (the text affected by the tag meaning) and the element's "End Tag". Elements are either block-level elements or inline elements. The following diagram shows the anatomy of an HTML Element.



<img src="./images/workbook_q1_markup-languages.jpg" width="814" alt="Control-Flow flow chart showing three types of Flow Control in Python">


---


## Q2:	**Define** the features of the following technologies that are essential in terms of the development of the internet:
 - packets
 - IP addresses (IPv4 and IPv6)
 - routers and routing
 - domains and DNS

> **Explain** how each technology has contributed to the development of the internet.

<br>

### 💲 __Solution__

```py
## Q2 solution goes here

```

---

## Q3:	**Define** the features of the following technologies that are essential in terms of the development of the internet:
 - TCP
 - HTTP and HTTPS
 - web browsers (requests, rendering and developer tools)

> **Explain** how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)

<br>

### 💲 __Solution__
```py
## Q3 solution goes here

```

---


## Q4:	**Identify** THREE data structures used in the Python programming language and **explain** the reasons for using each.

<br>

### 💲 __Solution__
```py
## Q4 solution goes here

```

---


## Q5:	**Describe** the features of interpreters and compilers and how they are different.

<br>

### 💲 __Solution__
```py
## Q5 solution goes here

```

---


## Q6:	**Identify** TWO commonly used programming languages and **explain** the benefits and drawbacks of each.

<br>

### 💲 __Solution__
```py
## Q6 solution goes here

```

---

## Q7:	**Identify** TWO ethical issues from the areas below and **discuss** the extent to which an IT professional is ethically responsible in terms of the issue.

List of topics containing ethical issues:
 - access to a user’s personal information (medical, family, financial, personal attributes such as sexuality, religion, or beliefs)
 - intellectual property, copyright, and acknowledgement.
 - criminal acts such as theft, fraud, trafficking and distribution of prohibited substances, terrorism
 - GPS tracking data and other types of metadata, MAC addresses, hardware fingerprints
 - freedom of thought, conscience, speech and the media
 - aggressive sales and marketing practices designed to mislead and deceive consumers
 - trading of shares on the stock exchange OR cryptocurrencies

> For each ethical issue identify a source of legal information relating to the ethical issue and discuss whether the
> law is helpful in assisting a developer to act in an ethical way. (Word count guide: 200 words max)

> Conduct **research** into a case study of **ONE** of the ethical issues you have chosen **discuss** how an ethical IT
> professional should respond to the case study and how they might mitigate or prevent ethical breaches. (Word count 
> guide: 400 - 600 words)

<br>

### 💲 __Solution__
```py
## Q7 solution goes here

```

---

###  *__Following questions are Python related__*

---

## Q8:	Explain control flow, using examples from the Python programming language

<br>
Control Flow is a term used in Python to describe the order in which a Python block of code will be executed.

In Python Control Flow can be divided into the three following categories show in the flow chart below

<br>


<img src="./images/T1A1_workbookQ8_control-flow.png" width="840" alt="Control-Flow flow chart showing three types of Flow Control in Python">

### 💲 __Solution__

### __Conditional Statements__

The following examples show a range of Conditional Statements using a 'Movie World Batman Roller Coaster Ride' and an BMI calculator.

<br>

### __```if``` statement__

<br>

The ```if``` statement is Pythons simplest form of a Control Statement.<br>

The ```if``` statement will take the condition in which it will be evaluated to either ```true``` or ```false```.<br>

Following example shows ```height``` as the condition. If the user's height is greater than or equal to 120 centimetres then the condition is ```true```, and to print the following statement.

if the condition is ```false```, example the user's height is less than 120 centimetres and the condition is ```false``` and the block of code is skipped.
```py
height = 121

# condition: check if user is taller than or equal to 120cm 
if height >= 120:

    # statement: True  height is >= 120 then display this message
    print("Nice! You can ride the Batman rollercoaster, here is a complementary vomit bag")
```

<br>

### __```if-else``` statement__

<br>


The addition of the ```else``` component in the ```if-else``` statement allows Python to catch another condition.  The following example shows the addition of the ```else``` component.

The ```if-else``` statement will check the condition, if the condition evaluates to ```true``` then statement-1 will be executed, if the condition evaluates to ```false``` then statement-2 will be executed.


```py
height = 121

# condition: check if user is taller than or equal to 120cm 
if height >= 120:
    
    # statement-1: True  height is >= 120 then display this message
    print("Nice! You can ride the Batman rollercoaster, here is a complementary vomit bag")
    
    # statement-2: False in all other case (height < 120) display this message
else:
    print("Sorry bud your too short !")
```

<br>

### __```if-elif-else``` statement__

<br>

```py
height = float(input("enter your height in m: "))
weight = float(input("enter your weight in kg: "))
bmi = round(weight / height ** 2)

# condition-1 If BMI is less than 18.5kg
if bmi < 18.5:        

        # statement-1: underweight
        print(f"Your BMI is {bmi}, you are underweight")

# condition-2: If BMI is less than 25kg
elif bmi < 25:        

        # statement-2: normal weight
        print(f"Your BMI is {bmi}, you are in the normal weight range")

# condition-3: If BMI is over 25 but less than 30kg
elif bmi < 30:        

        # statement-3: overweight
        print(f"Your BMI is {bmi}, you are overweight")

# condition-4: If BMI is over 30 but less than 35kg
elif bmi < 35:        

        # statement-4: Fat
        print(f"Your BMI is {bmi}, you are fat!")

# condition n...
        ...    
        # you can add as many elif statements as you like, but they
        # must be within the 'if-else' condition.

# all other conditions: If BMI is less than 35 => 
else:      
    
    # statement: Super Fat
    print(f"Your BMI is {bmi}, you are super fat!")
```

### Nested if-else statement

```py

print("Welcome to the rollercoaster")

height = int(input("What is your height in cm ?"))

if height >= 120:
   
    print("You can ride the rollercoaster")
    age = int(input("What is your age ?"))
    
   
    if age < 12:   
        print("That will be $5 dollars please")
    elif age <= 18:     # age is 18 years or younger
        print("That will be $7 dollars please")
        #Note:
        #   1) We can use as many elif statement as we like, BUT must be in the
        #      if-else condition.
    else:       # age is over 18 years old (19 +)
        print("That will be $12 Dollars please")
else:
    print("Sorry bud your too short !")
```

---

## Q9:	Explain the difference between type coercion and type conversion. Are either of these used in Python?

<br>

### 💲 __Solution__
```sh
## Q9 solution goes here

```

---

## Q10: 	Explain data types, using examples


### 💲 __Solution__

There are many Python Data Types, but generally, a Python Data Type is a concept used to define some value stored in a variable. Data Types can take on different sizes and values and help you understand the operation needed to calculate some value.

For this workbook, the following 6 Python Data Types will be explained.


*   String (str)
*   integer (int)
*   float ()
*   boolean True / False
*   Range ()
*   List ()

<br>

### **String ( ) data type**

The data type ```string()``` is a string of characters that are created with double quotes.
The ```string()``` data type is useful for Subscripting, which is a method used for pulling
out particular elements from a string.
<br>

The following is an example of using the Subscripting method with the ```string()``` data type


```py
# The number in between the square brackets determines which character you're going to pull out.
# [0] = H, [1] = e, [2] = l, [3] = l, [4] = o

# Example-1:

print("Hello"[0])   #[0] output = letter "H"


# Example-2:

print("Hello"[4])  #[4] output = letter "o"
```
<br>

### **integer ( ) data type**

The data type ```integer()``` refers to a number with no decimal places (whole number). The ```int``` data type is 
useful for math operations.



```py
# Example: Math operation - adding integers


print(123 + 345)
# output = 468
# - Dont use qoutations("") when declearing Integers.


print(123_456_789) 
# output = 123456789
# - Use underscore(_) for when visualizing large numbers in code.
# - The computer will remove the underscores, and display the number as
#   if it was concatenated.
```


```py
# Example: Concatenating integers("string")


print("123" + "345")
# output = 123345
# Important: Anything inside quotations(" ") is just text (string).
```
<br>

### **float ( ) data type**

```float()``` also known as floating-Point Number 

```py
3.14159 # PI
3141.59
734_529.678

# - Floating-Point Number (Float).
# - The decimal point can float around a number because it could occur
#   at any point in the number.
```

### **Boolean values (True/False)**

```py
True
False

# - Booleans have only two values:
#       1) True
#       2) False
# - Booleans start with capital letters T/F
# - No quotation marks
# - Booleans used to test if something is True / False and for your
#   program to respond accordingly.
```

### **Range () data type**

```range()``` is a Python built-in function used for generating a sequence of numbers within a range of numbers
starting from 0 by default, and increments by 1 (by default), and stops before a specified number.

```py
# Basic range() syntax
range(start, stop)
```

```py
# Generate integer numbers
# start = 1, stop = 10
num = range(1, 10)


# iterate range using for loop
for num in range(1, 10):
    print(num, end=" ")
# Output 1 2 3 4 5 6 7 8 9 
# NOTE range() will output numbers from 1 to 10 but will NOT include 10


```


### **List () data type**

A ```list()``` is what you would call a Data Structure. It is a way of organizing and storing data in Python.
And are generally a way to keep an ordered sequence of multiple items in a single variable.
```py
# Example:

queensland_cities = ["Cairns", "Townsville", "Brisbane", "Gold Coast"]    

print(queensland_cities)
# output = Cairns Townsville Brisbane Gold Coast

```

---

## Q11:	Here’s the problem: “There is a restaurant serving a variety of food. The customers want to be able to buy food of their choice. All the staff just quit, how can you build an app to replace them?”
 - Identify the classes you would use to solve the problem
 - Write a short explanation of why you would use the classes you have identified

### 💲 __Solution__
```py
## 11 solution goes here

```

---

## Q12:	Identify and explain the error in the code snippet below that is preventing correct execution of the program

```python
celsius = input()
fahrenheit = (celsius * 9/5)+32
print(f"The result is: {fahrenheit}.")
```

### 💲 __Solution__

In Python, all inputs are Strings regardless of weather the user inputs a number
or a letter.

```py
# Include int function to change input String to Interger 
celsius = int(input()) # Str

# Missing ( ; ) at end of statement
fahrenheit = (celsius * 9/5)+32; # int

print(f"The result is: {fahrenheit}.")

# input = 30 degrees
# output = 86.0 fahrenheit
```

---

## Q13:	The code snippet below looks for the first two elements that are out of order and swaps them; however, it is not producing the correct results. Rewrite the code so that it works correctly.

```py
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0
while (i< arr.len() -1) and (arr[i] < arr[i+1]):
    i += i
print (i)
    arr[i] = arr[i+1]
    arr[i+1] = arr[i]
```


### 💲 __Solution__
```py
arr = [5, 22, 29, 39, 19, 51, 78, 96, 84]
i = 0

while (i < len(arr) -1) and (arr[i] < arr[i+1] ): 
    
    i = i + 1 

print(i)
j = arr[i]
arr[i] = arr[i + 1] 
arr[i + 1] = j
#output = [5, 22, 29, 19, 39, 51, 78, 96, 84]


```

---

## Q14:	Demonstrate your algorithmic thinking through completing the following two tasks, in order:
 1. Create a flowchart to outline the steps for listing all prime numbers between 1 and 100 (inclusive). Your flowchart should make use of standard conventions for flowcharts to indicate processes, tasks, actions, or operations
 2. Write pseudocode for the process outlined in your flowchart

<br>

### 💲 __Solution__

```py
## 14 solution goes here

```

---

## Q15:	Write pseudocode OR Python code for the following problem:
*You have access to two variables: raining (boolean) and temperature (integer). If it’s raining and the temperature is less than 15 degrees, print to the screen “It’s wet and cold”, if it is less than 15 but not raining print “It’s not raining but cold”. If it’s greater than or equal to 15 but not raining print “It’s warm but not raining”, and otherwise tell them “It’s warm and raining”*.

### 💲 __Solution__

```py
raining = True
temp = 15

def weather_forecast()

	if raining and temp < 15 degrees
		print("It’s wet and cold”)
	
	elif temp < 15 and != raining
		print("It’s not raining but cold”)
	
	elif temp >= 15 and != raining
		print("It’s warm but not raining”)
		
	else 
	    print("It’s warm and raining”)

weather_forecast()
```

---

## Q16:	ACME Corporation are hiring a new junior developer, as part of their hiring criteria they've created a "coding skill score" based on the specific competencies they require for this role; the more important the skill is for ACME corp, the more points it contributes to the "coding skill score" The skills are weighted as follows:
- Python (1)
- Ruby (2)
- Bash (4)
- Git (8)
- HTML (16)
- TDD (32)
- CSS (64)
- JavaScript (128)

>### **Write a program that allows a user to input their skills and then tells them:**

- a)Their overall "coding skill score" 
- b) Skills they may want to learn, and how much each one would improve their score


### 💲 __Solution__

```py

print("\nACME Corporation")

skills = ['python', 'ruby', 'bash', 'git', 'html', 'tdd', 'css', 'javascript']

scores = [1, 2, 4, 8, 16, 32, 64, 128]

userInput = []

print("\nEnter q to exit")
print("\nInput your coding skills (In words)")

uInput = str(input())
for i in range(0, len(skills)):
    if(uInput == 'q' or uInput == 'Q'):
        break
    if(uInput.lower() in skills):
        userInput.append(skills.index(uInput.lower()))
    uInput = str(input())

score = 0
for i in range(0, len(userInput)):
    score = score + scores[userInput[i]]

print("\nYour total coding skill score is", score)

print("\nYou may want to learn the following skills which will improve score by")
for i in range(0, len(skills)):
    if(i in userInput):
        continue
    print(skills[i], " ", score+int(scores[i]))

```

---