#Draft


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

# Getting Started

What is Luna



# The Basics

## Tables - AKA Arrays/Objects
Unlike other languages such as JavaScript, Luna calls objects/arrays "tables". Which serve as an array and object.

<!-- http://lua-users.org/wiki/TablesTutorial -->
<!-- https://developer.roblox.com/en-us/articles/Metatables -->
<!-- https://www.lua.org/pil/19.2.html -->
## Creating Table
{}

Asigning Values

Reading values

Good/Bad pratcie

## Getting all data from table and displaying it
Creating your own functions 

table.unpack()
table.remove()
table.add()





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