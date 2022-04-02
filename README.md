### In Progress (needs to be verified)
# Lua Unofficial Documentation


If you're comning from a language such as JavaScript or PHP, some differences are worth noting
```
Count starts from 1 not 0
0 does not mean false
1 does not mean true
```


# References (Alphabetic order)
## [Tables <small>AKA Array/Object</small>](#table)


===========================================================================


## <a name="table">Tables</a> <small>AKA Array/Object</small>
The 'table' allows storing a collection of data under a single variable.

```
Note:
When trying to print a table it will return you a table hash instead of the values such as: 0xd7b140
```

```
Note: The `table` object in other langauges woud be reffered as array/object
```

### Constructor 
`{}`
Creates a new `table` object(?).

### Properties

### Methods

[`table.insert()`](#table.insert)
Adds one element to the table.

[`table.remove()`](#table.remove)
Removed one element from the table.

[`table.concat()`](#table.concat)
Returns a new table that is the calling table with other table(s).

[`table.unpack()`](#table.unpack)
Unpacks a table into values.


===========================================================================


# <a name="table.insert">Table.insert()</a>
The `table.insert()` method adds one element to the start/start(?) of the table.

## Syntax
```lua
    table.insert(yourTable, value)
```

## Examples

### Adding elements to table

```lua

    groceries = { "Bread", "Rice"}
    table.insert(groceries, "Potatoes")

   -- Output:  groceries = {"Bread", "Rice", "Potattoes}

```


# <a name="table.remove">Table.remove()</a>
The `table.remove` method removes one element from the table.


## Syntax
```lua
    table.remove(yourTable, index)
```

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


# <a name="table.concat">Table.concat()</a>

# <a name="table.unpack">Table.unpack()</a>



## Table Plugins

table.clear



<details>


<summary>.</summary>

notes
.
.
.
.
.
.
.

# Other
## class
## function
## const

## for ... do
## whilte ... do
## pairs
## ipairs
## next
## rawset
## count

## return









@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@




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

