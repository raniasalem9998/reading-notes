# Read: 06 - JS Object Literals; The DOM

## HOW TO LEARN
 what you should do to learn is ***NOT*** shuveling loads of information to your brain ***BUT** to learn the basics and use your skills to improve in the topic. This way learning a new language will take from you less time but better resolts. Practicing is a key too not reading books and waiting others to be responsible on your learning journy,but sure you'll have to go to them for help But you need to Know how to search alone.

 ## JAVASCRIPT 
 ### WHAT IS AN OBJECT
 an object is avariable with propertirs (string,number 0r boolian) and mehtods like funtions.
 ``` javascript
 var person = {
  firstName: "rania",
  lastName: "qatawneh",
  age: 50,
  eyeColor: "brown"
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};
```
this refers to the owner of the funtion in this object .

To access an object method 
```javascript
objectName.methodName()
```
this can be useful when you want to work with multi semeler variables with some changes between them.

To update the object you use :
```javascript
objectName.property
or
objectName["property"]
or
objectName[expression] // x = "age"; person[x]
```
To make change*S* on the object you may use a funtion as a tamplet then use the ***new*** keyword to perform changes.

```javascript
function Dog (age) {
  this.age = age;
}

const doggie = new Dog(12);
```
### DOCUMENT OBJECT MODEL
A DOM TREE EXAMPLE:
- document
- html
- body
- div(attribute)
- ul(attribute)
- li(atrtribute)
- text (text nodes-cannot have children)
 - there are several keyworda to catch the element you want in the html document and make several changes to it or adding functions as well. which make it eiser to update your website .

 - catching dom queries:
 The querySelector() method returns the first element that matches a specified CSS selector(s) in the document. Note: The querySelector() method only returns the first element that matches the specified selectors. To return all the matches, use the querySelectorAll() method instead.
 [link1](https://www.w3schools.com/cssref/css_selectors.asp)
 [link2](https://www.w3schools.com/jsref/met_document_queryselector.asp)

 - to return asingle element node:
 ```html 
 getElementById('id')
 querySelector('css selector')
 ```
 - to return nodelist:
 ```
 getELementsByCllassName('class')
 get ElementByTagName('tagname')
 querySelectorAll('css')
 ```
 example:
 document.getElementById('one')
 object ->method->parameter
 -  you can loop throgh a node list using ***for***
 - selecting using the relation between elements is css alike.
 










