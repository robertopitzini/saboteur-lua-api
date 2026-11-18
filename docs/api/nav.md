# Nav

Navigation: moving to points and objects, formations, scripted paths.

23 functions.

## AddMemberToFormation

```lua
Nav.AddMemberToFormation(number, handle)
```

No result.

## BoardVehicle

```lua
Nav.BoardVehicle(handle, handle, string, boolean|integer, string, table, table)
```

No result.

## CancelFollowObject

```lua
Nav.CancelFollowObject(handle)
```

No result.

## CancelScriptedPath

```lua
Nav.CancelScriptedPath(handle)
```

No result.

## CanPathfind

```lua
Nav.CanPathfind(number, number, number, number, number, number, string, ?, table?)
```

No result.

## ChooseWanderPoint

```lua
Nav.ChooseWanderPoint()
```

No result. No arguments detected.

## CreateFormation

```lua
Nav.CreateFormation()
```

Returns a value. No arguments detected.

## EnableParadePath

```lua
Nav.EnableParadePath(string, boolean)
```

No result.

## EnterFormation

```lua
Nav.EnterFormation(handle, handle, number, number, number, number)
```

No result.

## ExitFormation

```lua
Nav.ExitFormation(handle)
```

No result.

## FollowObject

```lua
Nav.FollowObject(handle|string, handle|string, number, boolean|integer, boolean, boolean, boolean)
```

No result.

## FormationMoveOnPath

```lua
Nav.FormationMoveOnPath()
```

No result. No arguments detected.

## FormationMoveToPoint

```lua
Nav.FormationMoveToPoint(number, number, number, number)
```

No result.

## MoveToObject

```lua
Nav.MoveToObject(handle, handle, number, boolean|integer, string, ?, table, boolean, boolean, number)
```

No result.

## MoveToPoint

```lua
Nav.MoveToPoint(handle|string, number, number, number, boolean|integer, string, ?, table, number, boolean, number)
```

No result.

## SetFollowObjectBoardCallback

```lua
Nav.SetFollowObjectBoardCallback(handle, string, table, table)
```

No result.

## SetFollowObjectUnboardCallback

```lua
Nav.SetFollowObjectUnboardCallback(handle, string, table, table)
```

No result.

## SetScriptedPath

```lua
Nav.SetScriptedPath()
```

No result. No arguments detected.

## SetScriptedPathMoveMode

```lua
Nav.SetScriptedPathMoveMode(handle, boolean|number)
```

No result.

## SetScriptedPathSpeed

```lua
Nav.SetScriptedPathSpeed(handle, number, boolean)
```

No result.

## SetScriptedPathType

```lua
Nav.SetScriptedPathType(handle, number)
```

No result.

## StopMoving

```lua
Nav.StopMoving(handle)
```

No result.

## TreysMoveSeanToPointDangerous

```lua
Nav.TreysMoveSeanToPointDangerous(handle, number, boolean)
```

No result.
