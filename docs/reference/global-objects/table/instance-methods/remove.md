---
    title: table.remove()
    slug: /reference/global-objects/table/remove
---


The `table.remove()` method removes one element from the table and shifts it.


## Syntax
```Lua
table.remove(tbl, index)
```

## Parameter
`tbl`
The table where the item should be removed from.

`index`
The index (position) of the current element in the array.

## Examples
 Removing "Rice" from groceries table.

```Lua
groceries = { "Bread", "Rice", "Peas" }
table.remove(groceries, 2)

-- Output: groceries = { "Bread", "Peas" }
```
