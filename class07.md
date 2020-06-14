# HTML
- to make tables we use : tr(table row) and td)table data)attributes .
- th is used to comment on the table.
- you can assign the head and the foot for long tables.
- you can define the wedth of the element and its color also the border.
 # JAVASCRIPT
  you can do:
 - creat an obj. (:)
 - make changes on the obj.(= new)
 ```javascript
 var hotel = new Object();
hotel.name= 'Park';
hotel.rooms = 120;
hotel .booked = 77;
hotel .checkAvailability = function()
return this . rooms - this.booked;
} ;
var elName = document.getElementByid('hotelName');
elName.textContent = hotel . name;
var elRooms = document .getElementByid('rooms');
elRooms .textContent = hotel .checkAvailability(};
```
- (The+= operator is used to add
content to an existing variable.)
- there are 4 ways to creat an obj (p113).
- arrays in obj -> costs.room.item[i];
- obj in array -> costa[i].something;
- there are built in variables like dates, math,number...

