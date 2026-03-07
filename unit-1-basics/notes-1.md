# Unit 1 — Variables, Data Types & Collections 🐍

## 📌 Python Kya Hai? (History & Features)

<!-- YAHAN LIKHO: Python ke baare mein jo tumne samjha -->
<!-- Example: -->
<!-- Python ek high-level programming language hai jo Guido van Rossum ne banai... -->
Python is a high level interpreted with dynamic semantic programming language.

Ise sir Guido van russom ne 1991 me first version reliese kiya tha.

**Maine samjha:**
maine samjha python kafi simple and verstile hai iska use kai jagho par kiya jata hai jase web development, AI , machine learning , iot etc.

**Python kyun seekhein:**
- Python ka syntax bahut simple hai.
- Most popular prgramming language in the world .
- Verstile hai iska use karake ham kai sari chije kar sakate hai , jaise cyber security, web development, mobile app development, IOT , and machine learnig ai and automation etc.

---

## 🔧 Installation & Setup

<!-- Jo steps follow kiye install karne mein -->

**Steps jo maine kiye:**
1. sabase phale hame python ki official website par jakar `python.org` se uska installer file download karna hai apane system ke hisab se (windows,macOS,linux).
2. us installer file ko double tap karake open karna hoga/.
3. jo bhi chije puchhega use tick karake aage badhane hai fir hamar pyhon ka interpreter download ho jayega.

**Path set karna:**


---

## 📦 Variables

<!-- Variable kya hota hai — apne example se samjhao -->
Variable is a named of memory location . python me variable actual value store nahi karta keval usko refrence karata hai.

**Maine samjha:**

python me har chij ek object hota hai chahe vo integer ho ya string ho , everything is an object.

Python dynamic semantic hai yaani isme hame variable ka type nahi batana padata hai ki yah int , str, float ,double hai.
yah automatic detect kar leta hai.

**Rules jo yaad hain:**
- Variable name start with alphabates and underscore.
- not start number and special symbols.

**Example:**
```python
print("Hello world ") # display message on the screen
```
---

## 🔢 Numeric Data Types

| Type | Kya Hota Hai | Example |
|------|-------------|---------|
| int |integer numbers | -2,-1,0,1,2 |
| float |Decimal value | 2.09, 23.73|
| complex |imagnery numbers | 2+3i|

**Maine samjha:**
- `int data type:` isame `whole numbers` aate hai like `1 2 3 -3 -4 -2 0 etc.`

- `float data type:` isame hamare  `decimal valu` aate hai. jaise `2.34 3.143 etc.`

- `complex data type:` isame hame `imagenary numbers` ko represent karate hai. jaise ` 3+4i`  

---

## 📝 String Data Type & Operations

**String kya hai (mere shabdon mein):**

String is a sequence of characters.
ise inside double quotes `"strings"` likhate hai. 

**Important operations:**

| Operation | Kya Karta Hai | Example |
|-----------|--------------|---------|
| len() | Length find karna| len("hello") # 4|
| upper() |Text ko capitalize |print("hello".upper()) # HELLO  |
| lower() |Lowercase me karna |print("HELLO".lower()) # hello |


```python
# String practice code
name = "python"
last_name = "JAVA"
print(name.upper()) # 'PYTHON'
print(last_name.lower()) # 'java'
print(len(name)) # length of string is 5
```

---

## ➕ Basic Operators

| Operator | Type | Example |
|----------|------|---------|
| +, -, *, / | Arithmetic |2+5 |
| ==, !=, >, < | Comparison |5>7 |
| and, or, not | Logical |True and True |

**Jo confuse kiya pehle:**
- `and` oprtator me both side value `True` honi chahiye tabhi value true return hoti hai.
- `or` operator me atleast one side is `True`.
- `not` operator me `reverse` ho jati hai conditation
```python
# Both side should be 'True'
print(True and True) # result is 'True'
print(True and False) # result is 'False'
print(False and True) # result is 'False'
print(False and False) # result is 'False'

# one side is 'True' then result is true
print(True or True) # result is 'True'
print(True or False) # result is 'True'
print(False or True) # result is 'True'
print(False or False) # result is 'False'

# not oprator reverse the conditation
print(not True) # result is 'False'
print(not False) # result is 'True'
```


---

## 📋 List & List Slicing

**List kya hai (mere shabdon mein):**
- list multiple data ka collection hai jisame ham ek list banakar usame bahut saari data rakh sakate hai.

**List slicing samjha:**
```python
# Example:
my_list = [10, 20, 30, 40, 50]
# Yahan slicing try karo
slice = my_list[0:3]
print(slice) # 10,20,40 
```

---

## 🗂️ Other Data Types

### Tuple
**Mere shabdon mein:**


**List se fark:**


### Dictionary
**Mere shabdon mein:**


**Kab use karte hain:**


### Set
**Mere shabdon mein:**


**Special baat:**


---

## 📊 Comparison Table

| Type | Ordered | Changeable | Duplicates | Syntax |
|------|---------|-----------|-----------|--------|
| List | ✅ | ✅ | ✅ | `[ ]` |
| Tuple | ✅ | ❌ | ✅ | `( )` |
| Dictionary | ✅ | ✅ | ❌ Keys | `{ : }` |
| Set | ❌ | ✅ | ❌ | `{ }` |

---

## ❓ Jo Mujhe Confuse Kiya
-
-

## 💡 Maine Kya Seekha (Summary)
-
-

---
*Last Updated:*
