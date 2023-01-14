# T1A1-Workbook

---

## Q1: **Identify** and **explain** common and important components and concepts of web development markup languages.



### 💲 __Solution__


The first thing you see when visiting a particular website is a web page or document. These web pages contain markup 
languages such as Hypertext Markup Language (HTML). A website designer or front-end developer will use HTML to structure
and describe the content within these web pages.
 
An essential concept for markup languages such as HTML is that the nesting of HTML Elements defines the structure of an 
HTML document to form a hierarchy.
 
An HTML Element structure includes a "Start tag", a "Tag Name", and an "Attribute Name" with an "Attribute Value" of 
the "Element Content" (the text affected by the tag meaning) and the element's "End Tag". Elements are either 
block-level elements or inline elements. Figure 1 shows the anatomy of an HTML Element.


<img src="./images/workbook_q1_markup-languages.jpg" width="814" alt="Control-Flow flow chart showing three types of Flow Control in Python" height="448">
Figure-1 Anatomy of an HTML Element

---


## Q2:	**Define** the features of the following technologies that are essential in terms of the development of the internet:
 - packets
 - IP addresses (IPv4 and IPv6)
 - routers and routing
 - domains and DNS

> **Explain** how each technology has contributed to the development of the internet.


### 💲 __Solution__

<br>

#### Packets

The information transferred from one computer to another does not have to follow a fixed path, and the way for data 
transfer can change during a computer-to-computer interaction. Information goes from one computer to another in a 
"Packet" of information, and packet delivery depends upon network traffic on the route the packet is taking 
(Code.org, 2015, 0:01:27).

A Packet is a small segment of more extensive digital information or data, such as Music or Video. When data is sent 
over a computer network, such as the Internet, it is divided into pieces where the pieces might take different paths 
(Code.org, 2015, 0:02:19). Packets do not choose their route but have the IP address of where they are coming from and 
where they are going. Still, ultimately all packets arrive at their destination, where the packet data is recombined by
the device that receives them (Nimkarde, 2018).

<br>

#### IP Addresses (IPv4 and IPv6)

One of the most essential Protocols used in internet communication is the Internet Protocol or IP. An IP is a set of 
rules and standards used to communicate between machines, such as computers (Viles, 2022). Every computer is assigned a 
unique set of IP numbers to form an IP Address to send and receive data or Packets (Code.org, 2015, 0:03:01).

When you visit a website, your computer asks another computer on the network for information. Your computer sends a 
message to the other computer's IP Address along with its origin IP Address so the receiving computer knows where to 
send its response (Nimkarde, 2018).

Your computer currently has two IP Addresses, IPv4, an IP address standard established in the 1970s and IPv6, a new 
standard for IP Addresses. IPv4 is a 32-bit numbered address widely adopted in the 1980s and is a stable IP address 
standard for identifying over 4 billion devices on the internet (Code.org, 2015, 0:03:35). 

Due to the internet's popularity, the IP Address standard is transitioning from IPv4 to a new IP address standard 
called IPv6, a longer IP address format resulting in a 128-bit numbered address to provide a more significant amount of 
unique IP addresses for the increase of connected devices and the ongoing development of the internet 
(Code.org, 2015, 0:04:04).


<br>

#### Routers and Routing

Routers are special computers that act like internet traffic managers, keeping the packets moving through the networks 
smoothly by forwarding data packets between computer networks. As part of the Internet Protocol, each Router keeps 
track of multiple paths for sending packets and are connected to at least two paths at any given time 
(Code.org, 2015, 0:03:07).

Individual packets travel different routes through the internet if one route is congested. A Router will choose the 
most time-effective paths available for each piece of data based on the destination IP address for each Packet 
(Code.org, 2015, 0:03:34).

Factors that affect data routing are the relationship between companies and political roadblocks, so having multiple 
path options for sending data ensures the internet's reliability in data delivery (Code.org, 2015, 0:04:01).


<br>

#### Domains and DNS

Cloudflare (2019) describes the Domain Name System (DNS) as "the phonebook of the internet". Whenever we need to access 
information online, we first must identify the source of information, namely the website, to get information.

DNS associates the name of a website, such as `www.randomwebsite.com`, with corresponding IP addresses. 
Your computer uses DNS to look up Domain Names and get the associated IP Address used to connect your computer to the 
website on the internet (Code.org, 2015, 0:04:36).

The Domain Name System uses special computers called DNS servers, which are connected in a distributed hierarchy and 
divided into zones. The divided zones split up the responsibility in terms of better control over DNS components for 
the major Domains, such as .org, .com, .net, and .edu.

---

## Q3:	**Define** the features of the following technologies that are essential in terms of the development of the internet:
 - TCP
 - HTTP and HTTPS
 - web browsers (requests, rendering and developer tools)

> **Explain** how each technology has contributed to the development of client and server communication over the internet (50 - 150 words for each technology)


### 💲 __Solution__

<br>

#### Transmission Control Protocol (TCP)

__Transmission Control Protocol__ or __TCP__ manages the sending and receiving all your data as packets. When data 
packets arrive at your address, TCP checks if all packets have arrived and send back acknowledgements of each packet 
received. If all packets have been received, TCP signs off on only the complete packet delivery to ensure no data is 
lost (Code.org, 2015, 00:04:17). 

Actualizare (2022) describes TCP as providing a "reliable stream delivery of data between Internet hosts". 
In other words, the TCP system ensures that the data is undamaged, not lost or duplicated or out of order during its 
transit through the network. The TCP system is scalable, and to ensure the quality of client-server communication, 
TCP follows industry operating characteristics such as basic data transfer, reliability, flow control, multiplexing, 
connections, and precedence and security (Actualizare 2022).

<br>

#### HTTP and HTTPS

__Hypertext Transfer Protocol__ or __HTTP__ is an application protocol that expresses a formatted webpage to the web 
browser. We could think of HTTP as a language used to convey information between web browsers and servers.
The client (web browser) issues some commands to talk to a server (website), and in milliseconds that server starts to 
talk back to the client in HTTP (Goralski, 2017, p. 671).

The flexibility of the HTTP mechanism for transporting web content allows for the ongoing evolution of client-server 
communication. Markup languages such as hypertext markup language (HTML), cascading style sheets (CSS), and programming
languages are easily integrated with the HTTP method. HTTP is, however, an unsecured mechanism of communication between 
the client and server and requires a more secure connection, such as Hypertext Transfer Protocol Secure or HTTPS, to 
protect integrity and privacy during client-server data transfer (Goralski, 2017, p. 672). 

<br>

#### Web browsers (Request, Rendering and Developer Tools)

Wikipedia (2022) describes a Web browser as an "application software for accessing websites". Web browsers are built of 
frontend and backend technologies and work in a coordinated attempt at delivering a seamless web experience to the user.
Figure 2 shows the technologies and architecture of a web browser.

<img src="./images/T1A1_workbookQ3_web-browser.png" width="800" alt="Control-Flow flow chart showing three types of Flow Control in Python" height="500">
Figure-2 Web browser architecture

<br>


Web browsers play a pivotal role in accessing information on the internet. A user directly interacts with the web 
browser on their device via the User Interface (UI). UI is responsible for the visual elements of the browser, such as
input controls (dropdown list), navigation (search fields), and information components (notifications); without the UI,
for a general user, it would not be easy to interact with a computer system (Garrett, 2010).

Upon requesting content such as a webpage through the browser's UI, the rendering engine retrieves the content of the 
requested webpage. At the same time, the browser renders the requested content, such as HTML and XML elements and 
images styled using CSS, in the webpage to form the visual content displayed in the desired order or layout 
(Unadkat, 2022).

In addition to the web browser's ability to render retrieved content, most browsers include developer tools and 
generally appear alongside the rendered webpage within the browser. A developer uses developer tools for the design and 
engagement of webpages, and end users' engagement is a critical factor when designing webpages. Developers usually 
follow webpage and website design principles; developer tools are a powerful way to inspect, debug, emulate, and check 
the performance of webpages (Microsoft, 2022).


---


## Q4:	**Identify** THREE data structures used in the Python programming language and **explain** the reasons for using each.

<br>

### 💲 __Solution__
```py
## Q4 solution goes here

```

---


## Q5:	**Describe** the features of interpreters and compilers and how they are different.


### 💲 __Solution__

<br>

Interpreters and Compilers convert high-level programming languages into a computer's elemental language, known as 
machine code; however, there are several essential differences between Interpreters and Compilers (TechTarget, 2018).

The primary function of a __compiler__ is to create an executable program by translating a high-level programming language 
(source code) into a low-level programming language or machine code. An __interpreter__ can directly execute the 
instructions written in the high-level programming language without compiling or translating the programming language 
into machine code (Geeksforgeeks, 2022). Table-1 shows the difference between interpreters and compilers 
(Programiz, n.d).

<br>

<img src="./images/T1A1_workbookQ5-table.jpg" width="1000" alt="Control-Flow flow chart showing three types of Flow Control in Python" height="1200">








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