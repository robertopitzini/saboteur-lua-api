# Combat

Combat AI: targets, objectives, idle behaviour, melee.

65 functions.

## AddTargetFlag

```lua
Combat.AddTargetFlag(handle, number, table)
```

No result.

## BroadcastRetreat

```lua
Combat.BroadcastRetreat(handle, number, number)
```

No result.

## BroadcastSound

```lua
Combat.BroadcastSound(handle|number, number, number)
```

No result.

## ClearLeader

```lua
Combat.ClearLeader(handle)
```

No result.

## ClearObjective

```lua
Combat.ClearObjective(handle)
```

No result.

## ClearStateLock

```lua
Combat.ClearStateLock(handle)
```

No result.

## ClearTarget

```lua
Combat.ClearTarget(handle)
```

No result.

## ClearTargetFlags

```lua
Combat.ClearTargetFlags(handle)
```

No result.

## DoMeleeMove

```lua
Combat.DoMeleeMove(handle, string, handle, boolean)
```

No result.

## Exit

```lua
Combat.Exit(handle)
```

No result.

## GetMeleeHandleByName

```lua
Combat.GetMeleeHandleByName(string)
```

Returns a value.

## GetTarget

```lua
Combat.GetTarget(handle)
```

Returns a value.

## GlobalAllowGrenades

```lua
Combat.GlobalAllowGrenades(boolean)
```

No result.

## IsCombatant

```lua
Combat.IsCombatant(handle)
```

Returns a value.

## LockIntoMelee

```lua
Combat.LockIntoMelee(handle)
```

No result.

## LockIntoRanged

```lua
Combat.LockIntoRanged(handle)
```

No result.

## RemoveTargetFlag

```lua
Combat.RemoveTargetFlag(handle, number)
```

No result.

## RequestMeleeBP

```lua
Combat.RequestMeleeBP(handle, string)
```

No result.

## ResetPlayerTargetPriority

```lua
Combat.ResetPlayerTargetPriority()
```

No result. No arguments detected.

## ReturnToIdlePos

```lua
Combat.ReturnToIdlePos(handle)
```

No result.

## SetAimAndHitNoMiss

```lua
Combat.SetAimAndHitNoMiss(handle, boolean)
```

No result.

## SetAlwaysSeeTarget

```lua
Combat.SetAlwaysSeeTarget(handle, boolean)
```

No result.

## SetBroadcastEnteredCombat

```lua
Combat.SetBroadcastEnteredCombat(handle, boolean)
```

No result.

## SetBroadcastWeaponFire

```lua
Combat.SetBroadcastWeaponFire(handle, boolean)
```

No result.

## SetCombat

```lua
Combat.SetCombat(handle)
```

No result.

## SetDoMeleeCallbacks

```lua
Combat.SetDoMeleeCallbacks(handle, boolean)
```

No result.

## SetDryFire

```lua
Combat.SetDryFire(handle, boolean)
```

No result.

## SetFollowBoardCallback

```lua
Combat.SetFollowBoardCallback(handle, string, table, table)
```

No result.

## SetFollowUnboardCallback

```lua
Combat.SetFollowUnboardCallback(handle, string, table, table)
```

No result.

## SetGlobalAllowCombatHijacking

```lua
Combat.SetGlobalAllowCombatHijacking(boolean)
```

No result.

## SetGlobalHostileToResistance

```lua
Combat.SetGlobalHostileToResistance(boolean)
```

No result.

## SetGrabbable

```lua
Combat.SetGrabbable(handle, boolean)
```

No result.

## SetHostileTargetsOnly

```lua
Combat.SetHostileTargetsOnly(handle, boolean)
```

No result.

## SetHunt

```lua
Combat.SetHunt(handle, handle|number?, number, number)
```

No result.

## SetIdleAngle

```lua
Combat.SetIdleAngle(handle, number)
```

No result.

## SetIdleAttrPt

```lua
Combat.SetIdleAttrPt(handle, string, string)
```

No result.

## SetIdleDisperse

```lua
Combat.SetIdleDisperse(handle, boolean)
```

No result.

## SetIdleHoldWeapon

```lua
Combat.SetIdleHoldWeapon(handle, boolean)
```

No result.

## SetIdlePath

```lua
Combat.SetIdlePath(handle, string, number)
```

No result.

## SetIdlePos

```lua
Combat.SetIdlePos(handle|number, number, number)
```

No result.

## SetIdleScripted

```lua
Combat.SetIdleScripted(handle, boolean)
```

No result.

## SetIdleUseNeeds

```lua
Combat.SetIdleUseNeeds(handle, boolean)
```

No result.

## SetIgnoreCombatInVehicle

```lua
Combat.SetIgnoreCombatInVehicle(handle, boolean)
```

No result.

## SetLeader

```lua
Combat.SetLeader(handle, handle, boolean, number, number)
```

No result.

## SetLethalForce

```lua
Combat.SetLethalForce(handle, boolean)
```

No result.

## SetObjective

```lua
Combat.SetObjective(handle, handle, boolean, number, boolean)
```

No result.

## SetObjectivePath

```lua
Combat.SetObjectivePath(handle, handle, boolean, number)
```

No result.

## SetPlayerTargetPriority

```lua
Combat.SetPlayerTargetPriority(number)
```

No result.

## SetReactImmediately

```lua
Combat.SetReactImmediately(handle, boolean)
```

No result.

## SetRespondToDamage

```lua
Combat.SetRespondToDamage(handle, boolean)
```

No result.

## SetRespondToDeadBodies

```lua
Combat.SetRespondToDeadBodies(handle, boolean)
```

No result.

## SetRespondToEvents

```lua
Combat.SetRespondToEvents(handle, boolean)
```

No result.

## SetRespondToFriendlyDamage

```lua
Combat.SetRespondToFriendlyDamage(handle, boolean)
```

No result.

## SetRespondToPaperCheckEvent

```lua
Combat.SetRespondToPaperCheckEvent(handle, boolean)
```

No result.

## SetRespondToSound

```lua
Combat.SetRespondToSound(handle, boolean)
```

No result.

## SetSquadAssist

```lua
Combat.SetSquadAssist(handle, boolean)
```

No result.

## SetStationary

```lua
Combat.SetStationary(handle, boolean)
```

No result.

## SetTarget

```lua
Combat.SetTarget(handle, handle)
```

No result.

## SetTargetAggressively

```lua
Combat.SetTargetAggressively(handle, boolean)
```

No result.

## SetTargetTeam

```lua
Combat.SetTargetTeam(handle, number)
```

No result.

## SetTether

```lua
Combat.SetTether(handle, handle|number?, number, number, number, number)
```

No result.

## SetWimpy

```lua
Combat.SetWimpy(handle, boolean)
```

No result.

## SetWimpyUntilProvoked

```lua
Combat.SetWimpyUntilProvoked(handle, boolean)
```

No result.

## ThrowGrenade

```lua
Combat.ThrowGrenade(handle)
```

No result.

## UnlockMeleeMove

```lua
Combat.UnlockMeleeMove(string, string, boolean)
```

No result.
