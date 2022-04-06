---
title: Table
---

`table` is a built in object 

## Description

## Constructor
`{}` Creates a new `table` object.  


## Functions
[`next()`](#reference_functions_next)  
[`getmetatable()`](#reference_functions_getmetatable)  
[`setmetatable()`](#reference_functions_setmetatable)  
[`rawset()`](#reference_functions_rawset)  
[`rawget()`](#reference_functions_rawget)  
[`pairs()`](#reference_functions_pairs)  
[`ipairs()`](#reference_functions_ipairs)  


## Methods
[`table.insert()`](#global-objects_table-method_insert)  
    Adds one element to the table.  

[`table.remove()`](#global-objects_table-method_remove)  
Removes one element from the table.  

[`table.pack()`](#global-objects_table-method_pack)  
Packs elements into a new table.  

[`table.unpack()`](#global-objects_table-method_unpack)  
Unpacks a table into values.  

[`table.concat()`](#global-objects_table-method_concat)  
Returns a combined string from a table.  

[`table.sort()`](#global-objects_table-method_sort)  
Sorts the values in a table.  

[`table.move()`](#global-objects_table-method_move)  
Moves elements from one table to another table and returns it.
 

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
