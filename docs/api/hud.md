# HUD

On-screen elements: objectives, markers, timers, tutorials, GPS.

57 functions.

## AddButtonPrompt

```lua
HUD.AddButtonPrompt(string, number)
```

Returns a value.

## AddContraband

```lua
HUD.AddContraband(number|string, string, ?, ?, ?, boolean)
```

No result.

## AddGroundDecal

```lua
HUD.AddGroundDecal(handle)
```

Returns a value.

## AddLoadScreenTutorials

```lua
HUD.AddLoadScreenTutorials(table)
```

No result.

## AddObjective

```lua
HUD.AddObjective(number, string, number, number, boolean, number, number)
```

Returns a value.

## AddProgressBarCallback

```lua
HUD.AddProgressBarCallback(number, string, number, table, table)
```

No result.

## AddSubtitle

```lua
HUD.AddSubtitle(string, number, number, number, number, string)
```

Returns a value.

## AddTimer

```lua
HUD.AddTimer(number, boolean, number, number, number, number)
```

No result.

## AddToolTip

```lua
HUD.AddToolTip(string, number, number, number, number)
```

Returns a value.

## AddUpdateBoxText

```lua
HUD.AddUpdateBoxText(string, number, number, number, number, boolean, handle|number)
```

Returns a value.

## ArrowOff

```lua
HUD.ArrowOff()
```

No result. No arguments detected.

## ArrowOn

```lua
HUD.ArrowOn()
```

No result. No arguments detected.

## ClearAllObjectiveMarkers

```lua
HUD.ClearAllObjectiveMarkers()
```

No result. No arguments detected.

## ClearAllObjectives

```lua
HUD.ClearAllObjectives()
```

No result. No arguments detected.

## ClearButtonPrompt

```lua
HUD.ClearButtonPrompt(number)
```

No result.

## ClearGPSCourse

```lua
HUD.ClearGPSCourse()
```

No result. No arguments detected.

## ClearGPSTarget

```lua
HUD.ClearGPSTarget()
```

No result. No arguments detected.

## ClearLoadScreenTutorials

```lua
HUD.ClearLoadScreenTutorials()
```

No result. No arguments detected.

## ClearPauseMenuPos

```lua
HUD.ClearPauseMenuPos()
```

No result. No arguments detected.

## ClearTutorialText

```lua
HUD.ClearTutorialText()
```

No result. No arguments detected.

## ClearWaypoint

```lua
HUD.ClearWaypoint()
```

No result. No arguments detected.

## FlashObjectiveMarker

```lua
HUD.FlashObjectiveMarker(handle)
```

Returns a value.

## FlashRestrictedAreas

```lua
HUD.FlashRestrictedAreas()
```

No result. No arguments detected.

## GetProgressBarValue

```lua
HUD.GetProgressBarValue(number)
```

Returns a value.

## GetWaypointPosition

```lua
HUD.GetWaypointPosition()
```

Returns a value. No arguments detected.

## HasWaypoint

```lua
HUD.HasWaypoint()
```

Returns a value. No arguments detected.

## KeepObjectivesVisible

```lua
HUD.KeepObjectivesVisible(boolean)
```

No result.

## LoadObject

```lua
HUD.LoadObject(number, string)
```

No result.

## ModifyMessageColor

```lua
HUD.ModifyMessageColor(number, handle, number, number, number)
```

No result.

## ModifyMessageString

```lua
HUD.ModifyMessageString(number, handle, string)
```

No result.

## PauseTimer

```lua
HUD.PauseTimer(boolean)
```

No result.

## PlayAdvancedTutorial

```lua
HUD.PlayAdvancedTutorial(number, string, table, table)
```

No result.

## RemoveCheckpointFromMap

```lua
HUD.RemoveCheckpointFromMap(number, number, number)
```

No result.

## RemoveGroundDecal

```lua
HUD.RemoveGroundDecal(handle)
```

Returns a value.

## RemoveMessage

```lua
HUD.RemoveMessage(number, handle)
```

No result.

## RemoveObjective

```lua
HUD.RemoveObjective(number, boolean)
```

No result.

## RemoveObjectiveMarker

```lua
HUD.RemoveObjectiveMarker(handle)
```

Returns a value.

## RemoveTimer

```lua
HUD.RemoveTimer()
```

No result. No arguments detected.

## SetEnableAllGPSEdgesInTrigger

```lua
HUD.SetEnableAllGPSEdgesInTrigger(string, boolean)
```

No result.

## SetGPSCourse

```lua
HUD.SetGPSCourse(string)
```

No result.

## SetGPSTarget

```lua
HUD.SetGPSTarget(handle|number, number)
```

No result.

## SetGPSTargetToFocus

```lua
HUD.SetGPSTargetToFocus()
```

No result. No arguments detected.

## SetMinimapZoom

```lua
HUD.SetMinimapZoom(boolean, number)
```

No result.

## SetObjectiveMarker

```lua
HUD.SetObjectiveMarker(handle, number, number, boolean, boolean, boolean, number, string)
```

Returns a value.

## SetObjectiveStatus

```lua
HUD.SetObjectiveStatus(number, number)
```

No result.

## SetObjectiveText

```lua
HUD.SetObjectiveText(number, string)
```

No result.

## SetPauseMenuPos

```lua
HUD.SetPauseMenuPos(number, number, number)
```

No result.

## SetProgressBarValue

```lua
HUD.SetProgressBarValue(number, number)
```

No result.

## SetTemplate

```lua
HUD.SetTemplate(number)
```

No result.

## SetTransitionScreenParams

```lua
HUD.SetTransitionScreenParams(string?, string, string)
```

No result.

## SetTutorialText

```lua
HUD.SetTutorialText(number, string, string)
```

Returns a value.

## SetupProgressBar

```lua
HUD.SetupProgressBar(number, handle|number, number, number)
```

No result.

## SetWaypoint

```lua
HUD.SetWaypoint(number, number, number)
```

No result.

## ShowMissionTitle

```lua
HUD.ShowMissionTitle(string, string)
```

No result.

## ShowObjectiveMarker

```lua
HUD.ShowObjectiveMarker(handle, boolean, boolean)
```

No result.

## StartMiniGame

```lua
HUD.StartMiniGame(string)
```

No result.

## UnloadObject

```lua
HUD.UnloadObject(number)
```

No result.
