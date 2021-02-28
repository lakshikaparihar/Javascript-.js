## Primitive Types
* Number (Numeric Value)
* String (Text)
* Boolean (true and false)
* Null
* Undefined
* Symbol
* BigInt

----
----
> Shortcut to open console in Vivaldi  (Ctrl+Shift+I)
----

> To clear the console we use clear()

---
> To ignore any line or statement in js we use comments //
---
---
<br>

### Operators in JS

* Addition (+) or +=
* Multiplication (*) or *=
* Division (/) or /=
* Subtraction (-) or -=
* Modulus (%) or %=
* Exponential (**) 
* Increment (++)
* Decrement (--)

<br>

---
---

<strong>NaN</strong> is  NOT A NUMBER : It's a numeric value that represents something that is not a number (It's basically means that js is having a hard time to represent that number)

* <strong>Example :</strong> 
    * 0/0 gives NaN
    * 1 + NaN gives NaN


### __Some other special values JS has__

* **Infinity** : 1/0
* **-Infinity** : -1/0
* **-0** : negative is also a value in JS

---
---
<br>

> **New Syntax :**  let varName = value

> **Old Syntax :** var varName = value

---

> **Camel Casing** : first letter of first words should be small and later on it should be capital
* Example : numOfRating , whatIsThis

---
---

**Const** : cannot change it latter on
* Example : pi , daysInWeek etc.

> const a = 17 ; 

> a +=1  // error

* Can't have a variable of same name even if one is let and other is const

* Variable can change their data type

---
---

<br>

> To check the type of a variable we use **typeof**
Example : typeof 87
<br>

---
---

Use the combination of single and Double quote when you want quote inside of string

* String Concatenation(str1 + " "+ str2)
   
  * Example: "hi" + 1 ---> hi1 (it will covert 1 into a string)

* String is indexed starting from 0 and can be accessed but can't be modified

#### String Properties
* String.length

> To get the last character of a string we can do it like this a[a.length - 1]

* String.toUpperCase()
* String.toLowerCase()

> original value is unchanged until we change it manually

* String.trim() : Removes space from begining and ending of a string

* String.indexOf(substring) : In which index this substring belong

> Remember if you are finding the substring then it will return the index of the first charcter of the substring and if not found then -1

* String.slice(start , end(optional and exclusive))

> return empty string if there is nothing to slice

* String.replace(what , replace with) 
    * "ha ha ha".replace('ha','hee') :==> "hee ha ha"