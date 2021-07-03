# Object-Oriented Programming, HTML Tables

### BASIC TABLE STRUCTURE :
- `<table>`:  create a table. The contents 
of the table are written out row 
by row
- `<tr>` :You indicate the start of each 
row using the opening <tr> tag
- `<td>` : Each cell of a table is 
represented using a <td> 
element. (The td stands for 
table data.
- `<th>` : Table headding : The `<th>` element is used just 
like the  `<td>` element but its 
purpose is to represent the 
heading for either a column or 
a row. (The th stands for table 

## Functions, Methods, and Objects : 

### Objects : 
- Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names.

`var hotel = {`<br>
 `name : 1 Quay 1,`<br>
` rooms : 40 ,`<br>
 `booked:25,`<br>
 `gym: true,`<br>

` CheckAvailability : function``() {`
     `return this.rooms - this.booked`
 `}`
`};`

### Accessing an object and dot notation : 
` var hotelName = hotel.name,`
`var roomsFree = hotel.checkAvailability ();`

### Updating an object : 

` hotel.name = 'Park'`
> to update the proparity of an object : 
`hotel ['name'] = 'park'`

### Creating a constructor : 

`function hotel (name,rooms,booked) ` 
`{this.name=name;
this.rooms=room;
this.booked=booked
this.checkAvailability = function (){
return this.rooms - this.booked}
}`

### creating an instance : 

`let ahmadhotel = new hotel { ..,..,..}`

### ADDING AND REMOVING PROPERITIES : 

`var hotel = {`<br>
 `name : 1 Quay 1,`<br>
` rooms : 40 ,`<br>
 `booked:25,`<br>
 `gym: true,`<br>

` CheckAvailability : function``() {`
     `return this.rooms - this.booked`
 `}`
`};`

- to add : <br>
`hotel.spa=true` 
and so on 
- to delete : <br>
`delete hotel.booked`
