---
sidebar_position: 6
---

# Controls

```lua
<bool> IsControlEnabled(int inputGroup, int control)
<bool> IsControlPressed(int inputGroup, int contorl)
<bool> IsControlReleased(int inputGroup, int control)
<bool> IsControlJustPressed(int inputGroup, int control)
<bool> IsControlJustReleased(int inputGroup, int control)
<int> GetControlValue(int inputGroup, int control)
<float> GetControlNormal(int inputGroup, int control)
<void> 0x5b73c77d9eb66e24(BOOL p0)
<float> 0x5b84d09cec5209c5(int inputGroup, int control)
<bool> SetControlNormal(int inputGroup, int control, float amount)
<bool> IsDisabledControlPressed(int inputGroup, int control)
<bool> IsDisabledControlJustPressed(int inputGroup, int control)
<bool> IsDisabledControlJustReleased(int inputGroup, int control)
<float> GetDisabledControlNormal(int inputGroup, int control)
<float> 0x4f8a26a890fd62fb(int inputGroup, int control)
<int> 0xd7d22f5592aed8ba(int p0)
<bool> IsInputDisabled(int inputGroup)
<bool> IsInputJustDisabled(int inputGroup)
<bool> SetCursorLocation(float x, float y)
<bool> 0x23f09eadc01449d6(BOOL p0)
<bool> 0x6cd79468a1e595c6(int inputGroup)
<char*> GetControlInstructionalButton(int inputGroup, int control, BOOL p2)
<char*> 0x80c2fd58d720c801(int inputGroup, int control, BOOL p2)
<void> 0x8290252fff36acb5(int p0, int red, int green, int blue)
<void> 0xcb0360efefb2580d(Any p0)
<void> SetPadShake(int p0, int duration, int frequency)
<void> 0x14d29bb12d47f68c(Any p0, Any p1, Any p2, Any p3, Any p4)
<void> StopPadShake(Any p0)
<void> 0xf239400e16c23e08(Any p0, Any p1)
<void> 0xa0cefcea390aab9b(Any p0)
<bool> IsLookInverted()
<bool> IsLookNotInverted()
<int> GetLocalPlayerAimState()
<any> 0x59b9a7af4c95133c()
<bool> 0x0f70731baccfbb96()
<bool> 0xfc859e2374407556()
<void> SetPlayerpadShakesWhenControllerDisabled(BOOL toggle)
<void> SetInputExclusive(int inputGroup, int control)
<void> DisableControlAction(int inputGroup, int control, BOOL disable)
<void> EnableControlAction(int inputGroup, int control, BOOL enable)
<void> DisableAllControlActions(int inputGroup)
<void> EnableAllControlActions(int inputGroup)
<bool> 0x3d42b92563939375(char* p0)
<bool> 0x4683149ed1dde7a1(char* p0)
<void> 0x643ed62d5ea3bebd()
<void> DisableInputGroup(int inputGroup)
```