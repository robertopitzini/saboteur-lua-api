# Reading signatures

A signature like `Actor.SetLabel(handle, string, boolean)` lists the arguments in order.

| Type | Meaning |
|---|---|
| `handle` | object, actor, vehicle or locator handle |
| `string` | string |
| `number` | number |
| `integer` | whole number |
| `boolean` | true or false |
| `table` | Lua table, or the name of a callback function |
| `any` | read by the function, type not known |
| `type?` | optional |
| `a\|b` | either type is accepted |

## Accuracy

The types were taken from the game code and are not documented anywhere by the developers. Optional
arguments are not always marked, and a function listed with *No arguments detected* may still read some.
Treat the types as a guide and test anything that matters.

## Handles

Functions such as `Util.GetHandleByName`, `Object.Spawn` and the actor and vehicle getters return handles.
Pass a handle back to any function that takes one. Many of them also accept a name string.

## Callbacks

A `table` argument at the end of a signature is usually callback data: the name of a function as a
string, plus a table with its parameters.
