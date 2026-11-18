# Actor

People: state, needs, animations, disguises, vehicle boarding.

111 functions.

## AddFaceExpression

```lua
Actor.AddFaceExpression(handle|string, string, number)
```

No result.

## AddNeed

```lua
Actor.AddNeed(handle, number, number)
```

No result.

## AddSafetyNeed

```lua
Actor.AddSafetyNeed(handle, number, handle|number, number, number)
```

No result.

## AreNeedsEnabled

```lua
Actor.AreNeedsEnabled(handle)
```

Returns a value.

## BoardVehicle

```lua
Actor.BoardVehicle(handle, handle, string, boolean)
```

No result.

## BroadcastScaryEvent

```lua
Actor.BroadcastScaryEvent(handle, number)
```

No result.

## CalcFacingTo

```lua
Actor.CalcFacingTo(handle, handle|number, number, number)
```

Returns a value.

## CancelAnimation

```lua
Actor.CancelAnimation(handle)
```

No result.

## CancelAttrPt

```lua
Actor.CancelAttrPt(handle, boolean)
```

No result.

## CancelAttrPtRequest

```lua
Actor.CancelAttrPtRequest(handle, boolean)
```

No result.

## ChangeModule

```lua
Actor.ChangeModule(handle, string)
```

No result.

## ClearRagdollCallback

```lua
Actor.ClearRagdollCallback(handle)
```

No result.

## EnableAllLongIdles

```lua
Actor.EnableAllLongIdles(handle, boolean)
```

No result.

## EnableLongIdle

```lua
Actor.EnableLongIdle(string, boolean)
```

No result.

## EnableNeed

```lua
Actor.EnableNeed(handle, integer, boolean)
```

No result.

## EnableNeeds

```lua
Actor.EnableNeeds(handle, boolean)
```

No result.

## EnableSchedule

```lua
Actor.EnableSchedule(handle, boolean)
```

No result.

## EnterSpecialKillMode

```lua
Actor.EnterSpecialKillMode(handle, handle, number, number)
```

No result.

## ExitSpecialKillMode

```lua
Actor.ExitSpecialKillMode()
```

No result. No arguments detected.

## FireCurrentWeapon

```lua
Actor.FireCurrentWeapon(handle, number)
```

No result.

## ForceLongIdle

```lua
Actor.ForceLongIdle(string, handle, string, ?, table)
```

No result.

## ForceSmoking

```lua
Actor.ForceSmoking(handle)
```

No result.

## GetActorDist

```lua
Actor.GetActorDist(handle, handle)
```

Returns a value.

## GetCurrentModule

```lua
Actor.GetCurrentModule(handle)
```

Returns a value.

## GetFacingDir

```lua
Actor.GetFacingDir(handle)
```

Returns a value.

## GetModuleInputs

```lua
Actor.GetModuleInputs()
```

Returns a value. No arguments detected.

## GetPosition

```lua
Actor.GetPosition(handle)
```

Returns a value.

## GetPredefinedModule

```lua
Actor.GetPredefinedModule()
```

Returns a value. No arguments detected.

## GetSelf

```lua
Actor.GetSelf(handle)
```

Returns a value.

## GetVehicle

```lua
Actor.GetVehicle(handle)
```

Returns a value.

## GetWeaponPitch

```lua
Actor.GetWeaponPitch(handle)
```

Returns a value.

## GlobalEnableHighWTFCivMelee

```lua
Actor.GlobalEnableHighWTFCivMelee(boolean)
```

No result.

## HasLabel

```lua
Actor.HasLabel(handle, string)
```

Returns a value.

## HasUseableDisguise

```lua
Actor.HasUseableDisguise(handle|string)
```

Returns a value.

## HolsterWeaponImmediate

```lua
Actor.HolsterWeaponImmediate(handle)
```

No result.

## Immolate

```lua
Actor.Immolate(handle)
```

No result.

## IsAlive

```lua
Actor.IsAlive(handle)
```

Returns a value.

## IsAShop

```lua
Actor.IsAShop(handle)
```

Returns a value.

## IsDisguisable

```lua
Actor.IsDisguisable(handle)
```

Returns a value.

## IsDisguised

```lua
Actor.IsDisguised(handle)
```

Returns a value.

## IsInCombat

```lua
Actor.IsInCombat(handle)
```

Returns a value.

## IsInHunt

```lua
Actor.IsInHunt(handle)
```

Returns a value.

## IsInIdle

```lua
Actor.IsInIdle(handle)
```

Returns a value.

## IsInInvestigate

```lua
Actor.IsInInvestigate(handle)
```

Returns a value.

## IsInVehicle

```lua
Actor.IsInVehicle(handle, boolean)
```

Returns a value.

## IsRagdollInWater

```lua
Actor.IsRagdollInWater(handle)
```

Returns a value.

## IsSlacker

```lua
Actor.IsSlacker(handle)
```

Returns a value.

## IsTalkable

```lua
Actor.IsTalkable(handle)
```

Returns a value.

## IsUsingAttrPt

```lua
Actor.IsUsingAttrPt(handle)
```

Returns a value.

## OverrideCombatAI

```lua
Actor.OverrideCombatAI(handle, boolean)
```

No result.

## PlayAnimation

```lua
Actor.PlayAnimation()
```

No result. No arguments detected.

## PlayAnimationToBone

```lua
Actor.PlayAnimationToBone(handle, string, handle, handle, string, ?, table)
```

No result.

## PlayAnimationToPoint

```lua
Actor.PlayAnimationToPoint(handle, string, number, number, number, number, number, number, boolean|string, string, table)
```

No result.

## PlayerBlockSabLighting

```lua
Actor.PlayerBlockSabLighting()
```

No result. No arguments detected.

## PlayerOnSabSetGrenadeToExplode

```lua
Actor.PlayerOnSabSetGrenadeToExplode(number)
```

No result.

## PlayLongIdle

```lua
Actor.PlayLongIdle(handle, string)
```

No result.

## PullFromVehicle

```lua
Actor.PullFromVehicle(handle, handle, string)
```

No result.

## Ragdoll

```lua
Actor.Ragdoll(handle)
```

No result.

## RegisterRagdollCallback

```lua
Actor.RegisterRagdollCallback(handle, string, table, table)
```

No result.

## RemoveDisguise

```lua
Actor.RemoveDisguise(handle|string)
```

No result.

## RequestAttrPt

```lua
Actor.RequestAttrPt(handle, handle)
```

No result.

## ResetFallDamageDeath

```lua
Actor.ResetFallDamageDeath()
```

No result. No arguments detected.

## ResetFallDamageMinSpeed

```lua
Actor.ResetFallDamageMinSpeed()
```

No result. No arguments detected.

## ResetFallDamageMult

```lua
Actor.ResetFallDamageMult()
```

No result. No arguments detected.

## ResetFallDamageRagdoll

```lua
Actor.ResetFallDamageRagdoll()
```

No result. No arguments detected.

## SetAnimPriority

```lua
Actor.SetAnimPriority(handle, number)
```

No result.

## SetAttrPt

```lua
Actor.SetAttrPt(handle, string)
```

No result.

## SetAutoSeatTransition

```lua
Actor.SetAutoSeatTransition(handle, boolean)
```

No result.

## SetAutoUnboardOnOtherTeamBoard

```lua
Actor.SetAutoUnboardOnOtherTeamBoard(handle, boolean)
```

No result.

## SetBailWhenVehicleOnFire

```lua
Actor.SetBailWhenVehicleOnFire(handle, boolean)
```

No result.

## SetBreadCrumbs

```lua
Actor.SetBreadCrumbs(handle, boolean)
```

No result.

## SetCannotGetOutOfSeat

```lua
Actor.SetCannotGetOutOfSeat(handle, boolean)
```

No result.

## SetDisguise

```lua
Actor.SetDisguise(handle|string, string, boolean)
```

No result.

## SetDistantRagdollSound

```lua
Actor.SetDistantRagdollSound(handle)
```

No result.

## SetDontSpawnDeadGuys

```lua
Actor.SetDontSpawnDeadGuys(boolean)
```

No result.

## SetDropWeaponWhenRagdolled

```lua
Actor.SetDropWeaponWhenRagdolled(handle, boolean)
```

No result.

## SetEscDespawnImmune

```lua
Actor.SetEscDespawnImmune(handle, boolean)
```

No result.

## SetFacingDir

```lua
Actor.SetFacingDir(handle, handle|number)
```

No result.

## SetFallDamageDeath

```lua
Actor.SetFallDamageDeath(number)
```

No result.

## SetFallDamageMinSpeed

```lua
Actor.SetFallDamageMinSpeed(number)
```

No result.

## SetFallDamageMult

```lua
Actor.SetFallDamageMult(number)
```

No result.

## SetFallDamageRagdoll

```lua
Actor.SetFallDamageRagdoll(number)
```

No result.

## SetForceRedInReticule

```lua
Actor.SetForceRedInReticule(handle, boolean)
```

No result.

## SetHealthRecoveryPct

```lua
Actor.SetHealthRecoveryPct(handle, number)
```

No result.

## SetLabel

```lua
Actor.SetLabel(handle, string, boolean)
```

No result.

## SetMissionCriticalNPC

```lua
Actor.SetMissionCriticalNPC(handle, boolean)
```

No result.

## SetModuleInputs

```lua
Actor.SetModuleInputs()
```

No result. No arguments detected.

## SetNeverBloodyDisguise

```lua
Actor.SetNeverBloodyDisguise(handle|string, boolean)
```

No result.

## SetNonKnockdownable

```lua
Actor.SetNonKnockdownable(handle, boolean)
```

No result.

## SetPanicEnabled

```lua
Actor.SetPanicEnabled(handle, boolean)
```

No result.

## SetPanicFleeingEnabled

```lua
Actor.SetPanicFleeingEnabled(handle, boolean)
```

No result.

## SetPanicMode

```lua
Actor.SetPanicMode(handle, number)
```

No result.

## SetPanicOnceMode

```lua
Actor.SetPanicOnceMode(handle, boolean)
```

No result.

## SetPanicWalkAwayEnabled

```lua
Actor.SetPanicWalkAwayEnabled(handle, boolean)
```

No result.

## SetPersistent

```lua
Actor.SetPersistent(handle, boolean)
```

No result.

## SetPlayerPlantedTrapCallback

```lua
Actor.SetPlayerPlantedTrapCallback(string)
```

No result.

## SetPredefinedModule

```lua
Actor.SetPredefinedModule()
```

No result. No arguments detected.

## SetReactorEnabled

```lua
Actor.SetReactorEnabled(handle, boolean)
```

No result.

## SetRunsFromFire

```lua
Actor.SetRunsFromFire(handle, boolean)
```

No result.

## SetSlowCollision

```lua
Actor.SetSlowCollision(handle, boolean)
```

No result.

## SetStuckBashEnabled

```lua
Actor.SetStuckBashEnabled(handle, boolean)
```

No result.

## SetTalkable

```lua
Actor.SetTalkable(handle, boolean, string, string, boolean)
```

No result.

## SetupShop

```lua
Actor.SetupShop(handle, string?, string?, string?, string?, string?, string?)
```

No result.

## SetUseHitReactions

```lua
Actor.SetUseHitReactions(handle, boolean)
```

No result.

## SetVehicleAvoidance

```lua
Actor.SetVehicleAvoidance(handle, boolean)
```

No result.

## SurgeonGeneral

```lua
Actor.SurgeonGeneral(boolean)
```

No result.

## TurnOnDude

```lua
Actor.TurnOnDude(handle, boolean)
```

No result.

## UnboardVehicle

```lua
Actor.UnboardVehicle(handle, boolean)
```

No result.

## UseAttrPt

```lua
Actor.UseAttrPt(handle, handle, string, ?, table?, boolean)
```

No result.

## UseSubAttrPt

```lua
Actor.UseSubAttrPt(handle, handle)
```

No result.

## WalkToDespawnLocation

```lua
Actor.WalkToDespawnLocation(handle, boolean)
```

No result.
