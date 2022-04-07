---
title: Table
---

`table` is a built in object 

## Description

## Constructor

`{}` Creates a new `table` object.  

## Functions

[`next()`](#reference_functions_next)  
&nbsp;&nbsp;&nbsp; 

[`getmetatable()`](#reference_functions_getmetatable)  
&nbsp;&nbsp;&nbsp; 

[`setmetatable()`](#reference_functions_setmetatable)  
&nbsp;&nbsp;&nbsp; 

[`rawset()`](#reference_functions_rawset)  
&nbsp;&nbsp;&nbsp; 

[`rawget()`](#reference_functions_rawget)  
&nbsp;&nbsp;&nbsp; 

[`pairs()`](#reference_functions_pairs)  
&nbsp;&nbsp;&nbsp; 

[`ipairs()`](#reference_functions_ipairs)  


## Instance Methods

[`table.insert()`](/reference/global-objects/table/insert)  
&nbsp;&nbsp;&nbsp; Adds one element to the table.  
    
[`table.remove()`](/reference/global-objects/table/remove)    
&nbsp;&nbsp;&nbsp; Removes one element from the table.  

[`table.pack()`](/reference/global-objects/table/pack)    
&nbsp;&nbsp;&nbsp; Packs elements into a new table.  

[`table.unpack()`](/reference/global-objects/table/unpack)    
&nbsp;&nbsp;&nbsp; Unpacks a table into values.  

[`table.concat()`](/reference/global-objects/table/concat)    
&nbsp;&nbsp;&nbsp; Returns a combined string from a table.  

[`table.sort()`](/reference/global-objects/table/sort)    
&nbsp;&nbsp;&nbsp; Sorts the values in a table.  

[`table.move()`](/reference/global-objects/table/move)    
&nbsp;&nbsp;&nbsp; Moves elements from one table to another table and returns it.
 
## Examples
This section provides examples of common table operations in Lua.

### Create a table

### Access an table item by its index

```lua
local groceries = {
    {
        id = 3421,
        name = "Dark Chocolate",
        price = "$1.99"
    },
    {
        id = 4843,
        name = "Lemon",
        price = "$0.69"
    },
    {
        id = 2903,
        name = "Blender",
        price = "$42.00"
    }
    
}

print(groceries[3].name)

-- Expecetd Output: Blender
```

### Display values of a table

```lua
local groceries = {
    {
        id = 3421,
        name = "Dark Chocolate",
        price = "$1.99"
    },
    {
        id = 4843,
        name = "Lemon",
        price = "$0.69"
    },
    {
        id = 2903,
        name = "Blender",
        price = "$42.00"
    }
}

for index, data in ipairs(groceries) do
    print(index)

    for key, value in pairs(data) do
        print('\t', key, value)
    end
end

-- Expectd output:
-- 1
--   name	Dark Chocolate
--   price	$1.99
--   id	3421
-- 2
--   name	Lemon
--   price	$0.69
--   id	4843
-- 3
--   name	Blender
--   price	$42.00
--   id	2903
```


### Reasemblance of a Class

```lua
local Class = {}

function Class.makeSound(sound)
    return sound
end

function Class.sit()
-- code...
end

print(Class.makeSound("Woof!"))

-- Output: Woof
```


<!-- NOTES FROM OTHER PEOPLE WANTING TO DO X








oh ok, so if i had
Table = {
A,
B,
C
}

and i used Table [2] = nil

Table[2] would now be C?
or would Table[2] still exist, but just be nil

if i wanted to remove the last entry of a table, how would I do it?

table.remove(Table,#Table)?
stOne🪨 — 24/02/2022
table.remove moves everything after the index you deleted one index down so it can be a little slow, if you want to remove the last index do tableName[#tableName] its much faster


how do you spawn an object with the hash of it


 -->