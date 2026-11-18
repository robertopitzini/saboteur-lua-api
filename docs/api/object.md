# Object

Any game object: position, spawning, health, doors, spawners.

44 functions.

## Actuate

```lua
Object.Actuate(handle, boolean?)
```

No result.

## CreateSpawner

```lua
Object.CreateSpawner(string, number, number, number, number)
```

No result.

## Despawn

```lua
Object.Despawn(handle, number, boolean, boolean|number, boolean|number, number, boolean)
```

No result.

## EnableAnimatedPropPart

```lua
Object.EnableAnimatedPropPart(handle, boolean?, string?)
```

No result.

## EnableSpawner

```lua
Object.EnableSpawner(handle, boolean)
```

No result.

## ForceClose

```lua
Object.ForceClose(handle, boolean)
```

No result.

## ForceOpen

```lua
Object.ForceOpen(handle, boolean)
```

No result.

## GetAngle

```lua
Object.GetAngle(handle)
```

Returns a value.

## GetAttrPtAttachments

```lua
Object.GetAttrPtAttachments(handle)
```

Returns a value.

## GetBoneHandleFromCarriage

```lua
Object.GetBoneHandleFromCarriage(handle, boolean)
```

Returns a value.

## GetDistance

```lua
Object.GetDistance(handle, handle|number, number, number)
```

Returns a value.

## GetHealth

```lua
Object.GetHealth(handle)
```

Returns a value.

## GetMaxHealth

```lua
Object.GetMaxHealth(handle)
```

Returns a value.

## GetObjectsWithLabel

```lua
Object.GetObjectsWithLabel(handle|number, number, number)
```

Returns a value.

## GetPosition

```lua
Object.GetPosition(handle)
```

Returns a value.

## IsAlive

```lua
Object.IsAlive(handle)
```

Returns a value.

## IsAttrPt

```lua
Object.IsAttrPt(handle)
```

Returns a value.

## IsDead

```lua
Object.IsDead(handle)
```

Returns a value.

## IsDoorOpen

```lua
Object.IsDoorOpen(handle)
```

Returns a value.

## IsHuman

```lua
Object.IsHuman(handle)
```

Returns a value.

## IsInvincibleToAI

```lua
Object.IsInvincibleToAI(handle)
```

Returns a value.

## IsVehicle

```lua
Object.IsVehicle(handle)
```

Returns a value.

## Kill

```lua
Object.Kill(handle)
```

No result.

## LocatorSetParent

```lua
Object.LocatorSetParent(handle, handle)
```

No result.

## PlayerTeleportToLocator

```lua
Object.PlayerTeleportToLocator(handle)
```

No result.

## PlayerTeleportToPos

```lua
Object.PlayerTeleportToPos(number, number, number, number)
```

No result.

## SetDoorCloseDelay

```lua
Object.SetDoorCloseDelay(handle, number)
```

No result.

## SetGrenadeToExplode

```lua
Object.SetGrenadeToExplode(handle, number)
```

No result.

## SetHealth

```lua
Object.SetHealth(handle, number)
```

No result.

## SetInvincible

```lua
Object.SetInvincible(handle, boolean)
```

No result.

## SetInvincibleToAI

```lua
Object.SetInvincibleToAI(handle, boolean)
```

No result.

## SetKeyFramed

```lua
Object.SetKeyFramed(handle|string, boolean)
```

No result.

## SetOnActiveMission

```lua
Object.SetOnActiveMission(handle, boolean, boolean)
```

No result.

## SetOnTrappedCallback

```lua
Object.SetOnTrappedCallback(handle, string)
```

No result.

## SetShouldNeverRegisterGameObjectEvents

```lua
Object.SetShouldNeverRegisterGameObjectEvents(handle, boolean)
```

No result.

## Spawn

```lua
Object.Spawn(string, number, number, number, number, table?)
```

No result.

## SpawnAICrowdBlocker

```lua
Object.SpawnAICrowdBlocker(number, number, number, number, number, number, any?)
```

No result.

## SpawnerPurge

```lua
Object.SpawnerPurge(handle, boolean)
```

No result.

## SpawnerQueueSpawn

```lua
Object.SpawnerQueueSpawn(handle, string, string, table, table)
```

No result.

## SpawnerReset

```lua
Object.SpawnerReset(handle)
```

No result.

## SpawnFromList

```lua
Object.SpawnFromList(string, number, table)
```

No result.

## SpawnInVehicle

```lua
Object.SpawnInVehicle(string, string, handle, string, ?, table)
```

No result.

## SpawnOnRoad

```lua
Object.SpawnOnRoad()
```

No result. No arguments detected.

## Teleport

```lua
Object.Teleport(handle, number, number, number, number)
```

No result.
