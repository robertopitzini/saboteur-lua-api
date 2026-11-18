# Vehicle

Vehicles: seats, traffic, racing, callbacks.

81 functions.

## AddRacer

```lua
Vehicle.AddRacer(string, handle|string, string, number, number, number)
```

No result.

## AddToTraffic

```lua
Vehicle.AddToTraffic(handle|string, boolean, boolean, number, number, number)
```

No result.

## BrakeTo

```lua
Vehicle.BrakeTo(handle, number)
```

No result.

## CanBoard

```lua
Vehicle.CanBoard(handle, handle, handle|string)
```

Returns a value.

## CanPassengerGetOut

```lua
Vehicle.CanPassengerGetOut()
```

Returns a value. No arguments detected.

## ChangeSeat

```lua
Vehicle.ChangeSeat()
```

No result. No arguments detected.

## ClearDeathCallback

```lua
Vehicle.ClearDeathCallback(handle)
```

No result.

## Crash

```lua
Vehicle.Crash(handle|string, number, number, number, boolean)
```

No result.

## CreateRacer

```lua
Vehicle.CreateRacer(string, string, string, string, string, number, number, number)
```

No result.

## EnableInput

```lua
Vehicle.EnableInput(handle|string, boolean)
```

No result.

## EnableParked

```lua
Vehicle.EnableParked(boolean)
```

No result.

## EnableTraffic

```lua
Vehicle.EnableTraffic(boolean, boolean)
```

No result.

## ForceKeyframing

```lua
Vehicle.ForceKeyframing(handle)
```

No result.

## FreeRacer

```lua
Vehicle.FreeRacer(handle|string)
```

No result.

## FreeRacerWhenBehind

```lua
Vehicle.FreeRacerWhenBehind(handle|string)
```

No result.

## GetActorInSeat

```lua
Vehicle.GetActorInSeat(handle, string)
```

Returns a value.

## GetBoardingPosition

```lua
Vehicle.GetBoardingPosition(handle, string)
```

Returns a value.

## GetFireThreshold

```lua
Vehicle.GetFireThreshold(handle)
```

Returns a value.

## GetNextExitSeat

```lua
Vehicle.GetNextExitSeat()
```

Returns a value. No arguments detected.

## GetNumSeats

```lua
Vehicle.GetNumSeats(handle)
```

Returns a value.

## GetNumWheelsOnGround

```lua
Vehicle.GetNumWheelsOnGround(handle)
```

Returns a value.

## GetOccupantList

```lua
Vehicle.GetOccupantList(handle)
```

Returns a value.

## GetPassengers

```lua
Vehicle.GetPassengers(handle)
```

Returns a value.

## GetPilot

```lua
Vehicle.GetPilot(handle)
```

Returns a value.

## GetSeat

```lua
Vehicle.GetSeat(handle, handle)
```

Returns a value.

## GetSeatActor

```lua
Vehicle.GetSeatActor(handle, string)
```

Returns a value.

## GetSmokeThreshold

```lua
Vehicle.GetSmokeThreshold(handle)
```

Returns a value.

## GetSpeed

```lua
Vehicle.GetSpeed(handle)
```

Returns a value.

## HardSetLinVel

```lua
Vehicle.HardSetLinVel(handle, number)
```

No result.

## IsNaziVehicle

```lua
Vehicle.IsNaziVehicle(handle)
```

Returns a value.

## IsTrafficEnabled

```lua
Vehicle.IsTrafficEnabled()
```

Returns a value. No arguments detected.

## LockAllSeats

```lua
Vehicle.LockAllSeats(handle, boolean)
```

No result.

## LockSeat

```lua
Vehicle.LockSeat(handle, handle|string, boolean)
```

No result.

## MakeInvincible

```lua
Vehicle.MakeInvincible(handle, boolean)
```

No result.

## OverrideBraking

```lua
Vehicle.OverrideBraking(handle, boolean, number)
```

No result.

## OverrideHorsepower

```lua
Vehicle.OverrideHorsepower(handle, boolean, number)
```

No result.

## OverrideMaxSpeed

```lua
Vehicle.OverrideMaxSpeed(handle, boolean, number)
```

No result.

## RegisterWaterCallback

```lua
Vehicle.RegisterWaterCallback(handle, string, table, table)
```

No result.

## RegisterWaterLoggedCallback

```lua
Vehicle.RegisterWaterLoggedCallback(handle, string, table, table)
```

No result.

## RemoveFromTraffic

```lua
Vehicle.RemoveFromTraffic(handle|string)
```

No result.

## RemoveRacer

```lua
Vehicle.RemoveRacer(handle|string)
```

No result.

## SetAsMissionCritical

```lua
Vehicle.SetAsMissionCritical(handle, boolean)
```

No result.

## SetCanJoinEscalation

```lua
Vehicle.SetCanJoinEscalation(handle, boolean)
```

No result.

## SetCrashThrough

```lua
Vehicle.SetCrashThrough(handle|string, boolean)
```

No result.

## SetDeathCallback

```lua
Vehicle.SetDeathCallback(handle, string, table, table)
```

No result.

## SetForceAIController

```lua
Vehicle.SetForceAIController(handle, boolean)
```

No result.

## SetForceNeverFlip

```lua
Vehicle.SetForceNeverFlip(handle|string, boolean)
```

No result.

## SetForceSelfRight

```lua
Vehicle.SetForceSelfRight(handle|string, boolean)
```

No result.

## SetFullWheelRayScheduling

```lua
Vehicle.SetFullWheelRayScheduling(handle, boolean)
```

No result.

## SetMagicRacer

```lua
Vehicle.SetMagicRacer(handle, boolean)
```

No result.

## SetPinned

```lua
Vehicle.SetPinned(handle, boolean)
```

No result.

## SetPlayerLappedCallback

```lua
Vehicle.SetPlayerLappedCallback()
```

No result. No arguments detected.

## SetPlayerRoad

```lua
Vehicle.SetPlayerRoad(string)
```

No result.

## SetPlayerSpeedCallback

```lua
Vehicle.SetPlayerSpeedCallback(number)
```

No result.

## SetRaceCheckPointCallback

```lua
Vehicle.SetRaceCheckPointCallback()
```

No result. No arguments detected.

## SetRaceCollisionMultiplier

```lua
Vehicle.SetRaceCollisionMultiplier(number)
```

No result.

## SetRaceFinishedCallback

```lua
Vehicle.SetRaceFinishedCallback()
```

No result. No arguments detected.

## SetRaceLoadedCallback

```lua
Vehicle.SetRaceLoadedCallback()
```

No result. No arguments detected.

## SetRaceOffTrackCallback

```lua
Vehicle.SetRaceOffTrackCallback()
```

No result. No arguments detected.

## SetRacePlaceChangeCallback

```lua
Vehicle.SetRacePlaceChangeCallback()
```

No result. No arguments detected.

## SetRacerNearPlayerCallback

```lua
Vehicle.SetRacerNearPlayerCallback(number)
```

No result.

## SetRacerRoad

```lua
Vehicle.SetRacerRoad(handle|string, string)
```

No result.

## SetRacerSpeed

```lua
Vehicle.SetRacerSpeed(handle|string, number, number)
```

No result.

## SetRacerTarget

```lua
Vehicle.SetRacerTarget(handle|string, handle|string, number)
```

No result.

## SetRaceStartCallback

```lua
Vehicle.SetRaceStartCallback()
```

No result. No arguments detected.

## SetRaceWrongWayCallback

```lua
Vehicle.SetRaceWrongWayCallback()
```

No result. No arguments detected.

## SetRacing

```lua
Vehicle.SetRacing(boolean, boolean, number)
```

No result.

## SetStuckCallback

```lua
Vehicle.SetStuckCallback(handle, string)
```

No result.

## SetSuperHeavy

```lua
Vehicle.SetSuperHeavy(handle, boolean)
```

No result.

## SetTakeDamageInCinematic

```lua
Vehicle.SetTakeDamageInCinematic(handle, boolean)
```

No result.

## SetupRace

```lua
Vehicle.SetupRace(string)
```

No result.

## ShowRaceTimer

```lua
Vehicle.ShowRaceTimer(boolean, number)
```

No result.

## SpawnRacer

```lua
Vehicle.SpawnRacer(string, number, number, number)
```

No result.

## StartFireEffect

```lua
Vehicle.StartFireEffect(handle)
```

No result.

## StartPlayback

```lua
Vehicle.StartPlayback(handle, string, string, table, table)
```

No result.

## StartRaceTimer

```lua
Vehicle.StartRaceTimer(boolean)
```

Returns a value.

## StartSmokeEffect

```lua
Vehicle.StartSmokeEffect(handle)
```

No result.

## TrafficAccidentResponse

```lua
Vehicle.TrafficAccidentResponse(boolean)
```

No result.

## TurnHeadlightsOff

```lua
Vehicle.TurnHeadlightsOff(handle|string)
```

No result.

## TurnHeadlightsOn

```lua
Vehicle.TurnHeadlightsOn(handle|string, boolean)
```

No result.

## UnboardAll

```lua
Vehicle.UnboardAll(handle, boolean|table, string, table, table, string, table, table)
```

No result.
