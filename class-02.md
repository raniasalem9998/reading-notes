# Readings : Basics of HTML, CSS & JS

## **HTML**

### *TEXT*

- Headings are noted by: 
 ```html
     <h1> <h2> ... <h6>
 ```
 - The *p* is used to define paragraphes.
 - *b* for bold and i for italic font.
 - The *Sup* for supscript bur sub is for subscript.
 - White spaces are auto collapsed.
- *br* and *hr* are to for breaks between lines.
- *em* by defolt is italic but you can change it in css.
- You can use *blockquote* or *q* for smaller qouts.
- You can add auther details using *address*.
- *ins* and *del* are to underline or cross text contained.

### *INTRODUCING CSS*
CSS describes how HTML elements are to be displayed on screen, paper, or in other media.
###
CSS can be added to HTML elements in 3 ways:
###
Inline - by using the style attribute in HTML elements.
Internal - by using a *style* element in the *head* section.
External - by using an external CSS file.
###

## **JS**

### *BASIC*
- comments are added by 
```javascript
 /* multi line comment
 */
 //line comment
 ```
- Variable:save information
``` javascript
 var name = value 
 ```
 value can be
 * numberic 1 2 3
 * string "text"
 * boolean yes/no

- concatnation is mersing two or more variables to one 

```javascript
 document.write(var1+var2+var3)
 ```

### *DECISIONS AND LOOPS*

Loops are handy, if you want to run the same
code over and over again, each time with a different value.
 Instead of writing:
 ```javascript
        text += cars[0] + "<br>";
        text += cars[1] + "<br>";
        text += cars[2] + "<br>";
        text += cars[3] + "<br>";
        text += cars[4] + "<br>";
        text += cars[5] + "<br>";
 ```
 You can write:
 ```javascript
        var i;
        for (i = 0; i < cars.length; i++) { text +=cars[i] + "<br>" ; } 
 ```
 JavaScript supports different kinds of loops:
- for - loops through a block of code a number of times.
- for/in - loops through the properties of an object.
- for/of - loops through the values of an iterable object.
- while - loops through a block of code while a specified condition is true.
- while - loops through a block of code while a specified condition is true.
            