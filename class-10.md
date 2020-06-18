# Read: 10 - JS Debugging
 
 - consol and div tools are essintial in tracking errors in the code.
 - Know the order of calling your functions
 - when a funtion needs another js will pill it on top.
 - Notice the scope
 - you can see multi errors on the console screen that can help you 
 - in chrome the error will show you the type and the line of the error
 - you can group messeges like:
 ```javascript
 console .group( ' Area calculations');
console .i nfo('Width ' , width);
console .info( 'Height ', height);
consol e. l og(area); cY console.groupEnd();
;
``` 
- or a table:
```javascript
console.table(contacts); II Write data to console
var city, contactDetails;
contactDetails = '';
II De~lare variabl es for page
II Hold details wr itten to page
$.each(contacts , function(city, contacts) { II Loop t hrough data to
contactDetails += city+ ': ' +contacts.Tel + '<br I>' ;
} ) ;
$( ' h2').after('<p>' + contactDetails + '<Ip>'); II Add data to the page
```