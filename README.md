### In Progress
# Lua Unofficial Documentation


# Lua
What is Lua?

## Who is Lua for?

Lua is rarery use on its own, isntead its often embeded in other programs. 

Notable mentioens, Roblox, Adobe Photoshop Lightroom, Angry Birds, Cheat Engine, 


Its very popular in the gaming industry but also its been used in network and system programs. 

Modding
Feature Enhancement notable games Minecraft

Compact
Fast in execution
Highly extendable
Easy to learn
Free to use

## History of Luna

Lua was desinged by a team of of three Brazililian scientist, Roberto Ierusalimschy, Luiz Henrique de Figueiredo, and Waldemar Celes. The first Lua release was in 1993.

Brazil had a very stric import policy from 1984 untill 1992, which also included hardware.  Due to the hardware limitations in Brazil, the three scientist developed the scripting language, Lua.

The name comes from the world `luna` which is Brazilian way of saying `moon`.


===========================================================================


# References v
## [Tables AKA Array/Object](#table)
## [Select]
## [Math]
## [String]


===========================================================================


## <a name="table">Tables</a> <small>AKA Array/Object</small>
The 'table' allows storing a collection of data under a single variable. Lua has one mechanism to represent data structure, and does not contain `classes`, `arrays` and `objects`. Every data structure is reprresented by `table`.

The index starts at 1 instead of 0.

Table is an associative array

looping over tables `pairs` and `ipairs`


```
Note: When trying to print a table it will return you a table hash instead of the values such as: 0xd7b140
Note: The `table` object in other langauges woud be reffered as array/object
```

### Constructor 
`{}`
Creates a new `table`.

### Properties

### Methods

[`table.insert()`](#table-insert)
Adds one element to the table.

[`table.remove()`](#table-remove)
Removes one element from the table.

[`table.concat()`](#table-concat)
Returns a new table that is the calling table with other table(s). (???)

[`table.unpack()`](#table-unpack)
Unpacks a table into values.

[`table.sort()`](#table-sort)



===========================================================================


# <a name="table-insert">Table.insert()</a>
The `table.insert()` method adds one element to the start/end(?) of the table.

## Syntax
```lua
table.insert(yourTable, value)
```

## Parameter


## Examples

### Adding elements to table

```lua

groceries = { "Bread", "Rice"}
table.insert(groceries, "Potatoes")

-- Output:  groceries = {"Bread", "Rice", "Potattoes}

```


# <a name="table-remove">Table.remove()</a>
The `table.remove` method removes one element from the table.


## Syntax
```lua
table.remove(yourTable, index)
```

## Parameter


## Examples
 Removing "Bread" from groceries table.
 
This methods removed an item from table by index, and shifts the table.

```lua
groceries = { "Bread", "Rice"}
table.insert(groceries, 1)

-- Output: groceries = { "Rice" }
```

Removing a value without shifting

```lua
groceries = { "Bread", "Rice"}
groceries[1] = nil

-- Output: groceriees = { "Rice" }
```


Another way to delete is to use rawset???

# <a name="table-concat">Table.concat()</a>



# <a name="table-unpack">Table.unpack()</a>



# <a name="table-sort">Table.sort()</a>

The `table.sort()` sorts a table and returns its value sorted. If no value is provited, the sort function will default to alphabetical sorting.


## Syntax
```lua
table.sort(yourTable)

table.sort(yourTable, value)
```

## Parameters

## Examples





----------------------------------

# Plugins

## Table 
table.clear

## JSON
link to JSON decoder - http://dkolf.de/src/dkjson-lua.fsl/home


<details>


<summary>.</summary>


# Template


# Name
Description what it does

## Syntax
## Parameters
## Examples


notes
.
.
.
.
.
.
.





# I miss
## CLasses







@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@





@@@@

Lua com

21 reserved words
1 mechanism to represent data struture

Lua is a dynamic language, not type anotations needed


https://luarocks.org/


If you're comning from a language such as JavaScript or PHP, some differences are worth noting
```
Count starts from 1 not 0
0 does not mean false
1 does not mean true
```

@@@@


coroutine.create() - suspend and resume code
coroutine.yeld() - puse
courutine.resume() - continue executoin

# Reserved words

and
break
do
else
elseif
end
false
for ... do
function
if ... then
in
local
nil
not
or
repeat
return
then
true
until
while .... do

# Other
## const
 
## pairs
## ipairs
## next
## rawset
## count















<!-- Docs to look at: React, Laravel, JS MDN -->

Use real life examples, not some foo bar, a, e, i... 



# Comprehensive Guide for Lua by examples 


# Tables AKA Objects/Arrays

You can follow along and compile lua online without downloading it: https://replit.com/languages/lua

Official Download site for Lua:

## <a name='TOC'>Table of Contents</a>

  1. [Types](#types)

   ```lua
    -- bad
    woof

    -- good
     miao
    ```


    **[[⬆]](#TOC)**

    https://stackoverflow.com/questions/41942289/display-contents-of-tables-in-lua

## <a name='types'>Types</a>
JS Example

<const>

# Variables

In Lua to declaare a variable you simply write out the name

`variable`

if you want to you can also

`variable <const>`

# Scope

# Functions

# Tables aka Objects & Arrays

Lua doesn't have objects nor arrays - it has just tables. s
Tables in luas is Arr
Objects in Lua are called Tables. 
Objects in Lua are called Arrays.They serve as an array and object.

To insert into the database, you need to `table.insert(table, value)`

To unpack values from a table, you need to unpack(data)

If you print a table, you will see table hash therefore you need to use special pairs and ipairs to show the content


<!-- object.getHash() -->
<!-- object.print() -->
<!-- object.count() -->
<!-- object.insertTo(object, data) -->
<!-- object.removeFrom(data, index) -->
<!-- object.unpack(data) -->
<!-- object.returnHashes() -->
<!-- object.create -->

<!-- Lua utility -->

To access properties of tables, you need to use special functions. pairs and ipairs.

Here are a few ways to work with them.

JavaScript Example
```js


```

Lua Example
```

```


LUA Example
```
local people = {
    test = {
    ['99'] = {
         name = "Fred",
         address = "16 Long Street",
         phone = "123456"
     },
     ['8989'] = {
         name = "Wilma",
         address = "16 Long Street",
         phone = "123456"
        }
    }
}
```
  
--   for index, data in pairs(people.test) do
--       print(index)
  
--       -- for key, value in pairs(data) do
--       --     print('\t', key, value)
--       -- end
--   end
  
  -- hash breaks this 





lunavel.com

Lunavel, the unofficial documentation you were looking for Luna!
Get started


Asigning Values

Reading values

Good/Bad pratcie

Creating your own functions 







Built-In Globals
Lua Globals
Roblox Globals

Lua Libraries
coroutine
debug
math
os
string
table
utf8
bit32


# Working with JSON



# Have plugins
Copy and paste it in your file app/illuminate

- JSON - ability to decode JSON into Lua
- Table [ print table Content], not just hash









# Getting Started

## Meet Lua
Lua is a scripting language ...


### Why Lua?

What is Luna

#### Flexibile

### Starter Kits
<!-- Table addons plugin -->
<!-- JSON plugin -->


# Data Types
nil
boolean
number
string
function
userdata
thread
table

# Declearing Variables

groceries = {}
groceries <const> = {}


https://stackoverflow.com/questions/4880368/how-to-delete-all-elements-in-a-lua-table
# Statements and declerations





## Classes

## JSON
<!-- Lua doens't provide support for JSON, however there' is a package you can install to get support for it -->

<!-- Accessing values in tables -->


# Method explore - example
Short info 

<!-- list all methods  -->


# Property definition - Example Framework 
Explanation about the feature
<!-- Demo -->

## Syntax
<!-- code -->

## Description


## Examples







<!-- http://lua-users.org/wiki/TablesTutorial -->
<!-- https://developer.roblox.com/en-us/articles/Metatables -->
<!-- https://www.lua.org/pil/19.2.html -->


</details>

