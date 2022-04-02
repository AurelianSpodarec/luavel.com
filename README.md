#Draft





# References (Alphabetic order)



## Tables - AKA Arrays/Objects
The 'table' allows storing a collection of data under a single variable.

```
Note: The `table` object in other langauges woud be reffered as array/object
```

## Constructor 
`{}`
Creates a new `table` object(?).

## Properties

## Methods
[Types](#types)
[`table.insert()`](#table.insert)
Adds one or more elements to the table.

[`table.remove()`](#table.remove)
Removed one or more elements from the table.

[`table.concat()`](#table.concat)
Returns a new table that is the calling table with other table(s).

[`table.unpack()`](#table.unpack)
Unpacks a table into values.


================================
 
# <a name="table.insert">Table.insert()</a>
The `table.insert()` method adds one element to the end/start(?) of the table.

## Syntax
```lua
    table.insert(yourTable, value)
```

## Examples

### Adding elements to table

```lua

    groceries = { "Bread", "Rice"}
    table.insert(groceries, "Potatoes")

   -- Result:  {"Bread", "Rice", "Potattoes}

```

# <a name="table.remove">Table.remove()</a>

# <a name="table.concat">Table.concat()</a>

# <a name="table.unpack">Table.unpack()</a>









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


