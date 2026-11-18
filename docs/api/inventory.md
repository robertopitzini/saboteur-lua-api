# Inventory

Items, weapons, ammo and money.

18 functions.

## DetachItem

```lua
Inventory.DetachItem(handle, handle, boolean)
```

No result.

## EnableAmmoDrops

```lua
Inventory.EnableAmmoDrops(boolean)
```

No result.

## GetAmmoCount

```lua
Inventory.GetAmmoCount(handle, handle|string)
```

Returns a value.

## GetCountOfType

```lua
Inventory.GetCountOfType(handle, string)
```

Returns a value.

## GetItemOfType

```lua
Inventory.GetItemOfType(handle, string)
```

Returns a value.

## GetMaxDollars

```lua
Inventory.GetMaxDollars()
```

Returns a value. No arguments detected.

## GetMoney

```lua
Inventory.GetMoney()
```

Returns a value. No arguments detected.

## GiveAmmo

```lua
Inventory.GiveAmmo(handle, handle|string, number)
```

No result.

## GiveItem

```lua
Inventory.GiveItem(handle, handle|string, boolean, number)
```

No result.

## GiveMoney

```lua
Inventory.GiveMoney(number|string, number|string)
```

No result.

## HasAnyGuns

```lua
Inventory.HasAnyGuns(handle)
```

Returns a value.

## HasItem

```lua
Inventory.HasItem(handle, handle)
```

Returns a value.

## HasWeapon

```lua
Inventory.HasWeapon(handle)
```

Returns a value.

## HolsterWeapons

```lua
Inventory.HolsterWeapons(handle)
```

No result.

## List

```lua
Inventory.List(handle)
```

Returns a value.

## ListOfType

```lua
Inventory.ListOfType(handle, string)
```

Returns a value.

## RemoveAllWeapons

```lua
Inventory.RemoveAllWeapons(handle)
```

No result.

## SetMaxDollars

```lua
Inventory.SetMaxDollars(number)
```

No result.
