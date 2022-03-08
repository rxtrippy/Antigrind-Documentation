---
sidebar_position: 33
---

# UI

```lua
<void> BeginTextCommandBusyspinnerOn(char* string)
<void> EndTextCommandBusyString(int busySpinnerType)
<void> RemoveLoadingPrompt()
<void> RemoveBusySpinner()
<bool> IsLoadingPromptBeingDisplayed()
<pickup> 0xb2a592b04648a9cb()
<void> 0x9245e81072704b8a(BOOL p0)
<void> ShowCursorThisFrame()
<void> SetCursorSprite(int spriteId)
<void> 0x98215325a695e78a(BOOL p0)
<bool> 0x3d9acb1eb139e702()
<bool> 0x632b2940c67f4ea9(int scaleformHandle, Any* p1, Any* p2, Any* p3)
<void> 0x6f1554b0cc2089fa(BOOL p0)
<void> ClearNotificationsPos(float pos)
<void> 0x25f87b30c382fca7()
<void> 0xa8fdb297a8d25fba()
<void> RemoveNotification(int notificationId)
<void> 0xa13c11e1b5c06bfc()
<void> 0x583049884a2eee3c()
<void> ThefeedPause()
<void> ThefeedResume()
<bool> ThefeedIsPaused()
<void> 0xd4438c0564490e63()
<void> 0xb695e2cd0a2da9ee()
<int> GetCurrentNotification()
<void> 0x56c8b608cfd49854()
<void> ResetNotificationData()
<void> SetNotificationBackgroundColor(int hudIndex)
<void> SetNotificationFlashColor(int red, int green, int blue, int alpha)
<void> 0x17ad8c9706bdd88a(Any p0)
<void> 0x4a0c7c9bb10abb36(BOOL p0)
<void> 0xfdd85225b2dea55e()
<void> 0xfdec055ab549e328()
<void> 0x80fe4f3ab4e1b62a()
<void> 0xbae4f9b97cd43b30(BOOL p0)
<void> 0x317eba71d7543f52(Any* p0, Any* p1, Any* p2, Any* p3)
<void> BeginTextCommandThefeedPost(char* text)
<int> SetNotificationMessage(char* picName1, char* picName2, BOOL flash, int iconType, BOOL _nonExistent, char* sender, char* subject)
<int> SetNotificationMessage2(char* picName1, char* picName2, BOOL flash, int iconType, char* sender, char* subject)
<int> SetNotificationMessage3(char* picName1, char* picName2, BOOL p2, Any p3, char* p4, char* p5)
<int> SetNotificationMessage4(char* picName1, char* picName2, BOOL flash, int iconType, char* sender, char* subject, float duration)
<int> SetNotificationMessageClanTag(char* picName1, char* picName2, BOOL flash, int iconType, char* sender, char* subject, float duration, char* clanTag)
<int> SetNotificationMessageClanTag2(char* picName1, char* picName2, BOOL flash, int iconType1, char* sender, char* subject, float duration, char* clanTag, int iconType2, int p9)
<int> EndTextCommandThefeedPostTicker(BOOL blink, BOOL showInBrief)
<int> EndTextCommandThefeedPostTickerForced(BOOL blink, BOOL p1)
<int> DrawNotification3(BOOL blink, BOOL p1)
<int> DrawNotificationAward(char* p0, char* p1, int p2, int p3, char* p4)
<int> DrawNotificationApartmentInvite(BOOL p0, BOOL p1, int* p2, int p3, BOOL isLeader, BOOL unk0, int clanDesc, int R, int G, int B)
<int> EndTextCommandThefeedPostCrewtagWithGameName(BOOL p0, BOOL p1, int* p2, int p3, BOOL isLeader, BOOL unk0, int clanDesc, char* playerName, int R, int G, int B)
<int> DrawNotificationUnlock(char* unlockLabel, int iconType, char* unk2)
<int> DrawNotificationUnlock2(char* unlockLabel, int iconType, char* unk2, int fadeInTime)
<int> EndTextCommandThefeedPostUnlockTuWithColor(char* primaryText, int iconType, char* unk2, int fadeInTime, int primaryStyle, BOOL ignoreLoc)
<int> DrawNotification4(BOOL blink, BOOL p1)
<any> 0x8efccf6ec66d85e4(Any* p0, Any* p1, Any* p2, BOOL p3, BOOL p4)
<any> 0xb6871b0555b02996(Any* p0, Any* p1, Any p2, Any* p3, Any* p4, Any p5)
<int> DrawNotificationWithIcon(int type, int image, char* text)
<int> DrawNotificationWithButton(int type, char* button, char* text)
<void> BeginTextCommandPrint(char* GxtEntry)
<void> EndTextCommandPrint(int duration, BOOL drawImmediately)
<void> BeginTextCommandIsMessageDisplayed(char* text)
<bool> EndTextCommandIsMessageDisplayed()
<void> BeginTextCommandDisplayText(char* text)
<void> EndTextCommandDisplayText(float x, float y)
<void> BeginTextCommandWidth(char* text)
<float> EndTextCommandGetWidth(BOOL p0)
<void> BeginTextCommandLineCount(char* entry)
<int> GetTextScreenLineCount(float x, float y)
<void> BeginTextCommandDisplayHelp(char* inputType)
<void> EndTextCommandDisplayHelp(Any p0, BOOL loop, BOOL beep, int duration)
<void> BeginTextCommandIsThisHelpMessageBeingDisplayed(char* labelName)
<bool> EndTextCommandIsThisHelpMessageBeingDisplayed(int p0)
<void> BeginTextCommandSetBlipName(char* gxtentry)
<void> EndTextCommandSetBlipName(Blip blip)
<void> BeginTextCommandObjective(char* p0)
<void> EndTextCommandObjective(BOOL p0)
<void> BeginTextCommandClearPrint(char* text)
<void> EndTextCommandClearPrint()
<void> BeginTextCommandOverrideButtonText(char* p0)
<void> EndTextCommandOverrideButtonText(BOOL p0)
<void> AddTextComponentInteger(int value)
<void> AddTextComponentFloat(float value, int decimalPlaces)
<void> AddTextComponentSubstringTextLabel(char* labelName)
<void> AddTextComponentSubstringTextLabelHashKey(Hash gxtEntryHash)
<void> AddTextComponentSubstringBlipName(Blip blip)
<void> AddTextComponentSubstringPlayerName(char* text)
<void> AddTextComponentSubstringTime(int timestamp, int flags)
<void> AddTextComponentFormattedInteger(int value, BOOL commaSeparated)
<void> AddTextComponentSubstringPhoneNumber(char* p0, int p1)
<void> AddTextComponentSubstringWebsite(char* website)
<void> AddTextComponentSubstringKeyboardDisplay(char* p0)
<void> SetNotificationColorNext(int hudIndex)
<char*> GetTextSubstring(char* text, int position, int length)
<char*> GetTextSubstringSafe(char* text, int position, int length, int maxLength)
<char*> GetTextSubstringSlice(char* text, int startPosition, int endPosition)
<char*> GetLabelText(char* labelName)
<void> ClearPrints()
<void> ClearBrief()
<void> ClearAllHelpMessages()
<void> ClearThisPrint(char* p0)
<void> ClearSmallPrints()
<bool> DoesTextBlockExist(char* gxt)
<void> RequestAdditionalText(char* gxt, int slot)
<void> RequestAdditionalText2(char* gxt, int slot)
<bool> HasAdditionalTextLoaded(int slot)
<void> ClearAdditionalText(int p0, BOOL p1)
<bool> IsStreamingAdditionalText(int p0)
<bool> HasThisAdditionalTextLoaded(char* gxt, int slot)
<bool> IsMessageBeingDisplayed()
<bool> DoesTextLabelExist(char* gxt)
<int> GetLengthOfStringWithThisTextLabel(char* gxt)
<int> GetLengthOfLiteralString(char* string)
<int> GetLengthOfString(char* STRING)
<char*> GetStreetNameFromHashKey(Hash hash)
<bool> IsHudPreferenceSwitchedOn()
<bool> IsRadarPreferenceSwitchedOn()
<bool> IsSubtitlePreferenceSwitchedOn()
<void> DisplayHud(BOOL toggle)
<void> 0x7669f9e39dc17063()
<void> DisplayHudWhenPausedThisFrame()
<void> DisplayRadar(BOOL Toggle)
<bool> IsHudHidden()
<bool> IsRadarHidden()
<bool> IsRadarEnabled()
<void> SetBlipRoute(Blip blip, BOOL enabled)
<void> SetBlipRouteColour(Blip blip, int colour)
<void> AddNextMessageToPreviousBriefs(BOOL p0)
<void> 0x57d760d55f54e071(BOOL p0)
<void> RespondingAsTemp(float p0)
<void> SetRadarZoom(int zoomLevel)
<void> 0xf98e4b3e56afc7b1(Any p0, float p1)
<void> SetRadarZoomLevelThisFrame(float zoomLevel)
<void> 0xd2049635deb9c375()
<void> GetHudColour(int hudColorIndex, int* r, int* g, int* b, int* a)
<void> 0xd68a5ff8a3a89874(int r, int g, int b, int a)
<void> 0x16a304e6cb2bfab9(int r, int g, int b, int a)
<void> ReplaceHudColour(int hudColorIndex, int hudColorIndex2)
<void> SetHudColour(int hudColorIndex, int r, int g, int b, int a)
<void> FlashAbilityBar(BOOL toggle)
<void> SetAbilityBarValue(float value, float maxValue)
<void> FlashWantedDisplay(BOOL p0)
<void> 0xba8d65c1c65702e5(BOOL p0)
<float> GetTextScaleHeight(float size, int font)
<void> SetTextScale(float unk, float scale)
<void> SetTextColour(int red, int green, int blue, int alpha)
<void> SetTextCentre(BOOL align)
<void> SetTextRightJustify(BOOL toggle)
<void> SetTextJustification(int justifyType)
<void> SetTextWrap(float start, float end)
<void> SetTextLeading(BOOL p0)
<void> SetTextProportional(BOOL p0)
<void> SetTextFont(int fontType)
<void> SetTextDropShadow()
<void> SetTextDropshadow(int distance, int r, int g, int b, int a)
<void> SetTextOutline()
<void> SetTextEdge(int p0, int r, int g, int b, int a)
<void> SetTextRenderId(int renderId)
<int> GetDefaultScriptRendertargetRenderId()
<bool> RegisterNamedRendertarget(char* p0, BOOL p1)
<bool> IsNamedRendertargetRegistered(char* p0)
<bool> ReleaseNamedRendertarget(Any* p0)
<void> LinkNamedRendertarget(Hash hash)
<any> GetNamedRendertargetRenderId(char* p0)
<bool> IsNamedRendertargetLinked(Hash hash)
<void> ClearHelp(BOOL toggle)
<bool> IsHelpMessageOnScreen()
<bool> 0x214cd562a939246a()
<bool> IsHelpMessageBeingDisplayed()
<bool> IsHelpMessageFadingOut()
<bool> 0x4a9923385bdb9dad()
<int> GetBlipInfoIdIterator()
<int> GetNumberOfActiveBlips()
<blip> GetNextBlipInfoId(int blipSprite)
<blip> GetFirstBlipInfoId(int blipSprite)
<vector3> GetBlipInfoIdCoord(Blip blip)
<int> GetBlipInfoIdDisplay(Blip blip)
<int> GetBlipInfoIdType(Blip blip)
<entity> GetBlipInfoIdEntityIndex(Blip blip)
<pickup> GetBlipInfoIdPickupIndex(Blip blip)
<blip> GetBlipFromEntity(Entity entity)
<blip> AddBlipForRadius(float posX, float posY, float posZ, float radius)
<blip> AddBlipForEntity(Entity entity)
<blip> AddBlipForPickup(Pickup pickup)
<blip> AddBlipForCoord(float x, float y, float z)
<void> TriggerSonarBlip(float posX, float posY, float posZ, float radius, int p4)
<void> 0x60734cc207c9833c(BOOL p0)
<void> SetBlipCoords(Blip blip, float posX, float posY, float posZ)
<vector3> GetBlipCoords(Blip blip)
<void> SetBlipSprite(Blip blip, int spriteId)
<int> GetBlipSprite(Blip blip)
<void> SetBlipNameFromTextFile(Blip blip, char* gxtEntry)
<void> SetBlipNameToPlayerName(Blip blip, Player player)
<void> SetBlipAlpha(Blip blip, int alpha)
<int> GetBlipAlpha(Blip blip)
<void> SetBlipFade(Blip blip, int opacity, int duration)
<void> SetBlipRotation(Blip blip, int rotation)
<void> SetBlipFlashTimer(Blip blip, int duration)
<void> SetBlipFlashInterval(Blip blip, Any p1)
<void> SetBlipColour(Blip blip, int color)
<void> SetBlipSecondaryColour(Blip blip, float r, float g, float b)
<int> GetBlipColour(Blip blip)
<int> GetBlipHudColour(Blip blip)
<bool> IsBlipShortRange(Blip blip)
<bool> IsBlipOnMinimap(Blip blip)
<bool> 0xdd2238f57b977751(Any p0)
<void> 0x54318c915d27e4ce(Any p0, BOOL p1)
<void> SetBlipHighDetail(Blip blip, BOOL toggle)
<void> SetBlipAsMissionCreatorBlip(Blip blip, BOOL toggle)
<bool> IsMissionCreatorBlip(Blip blip)
<blip> DisableBlipNameForVar()
<bool> 0x4167efe0527d706e()
<void> 0xf1a6c18b35bcade6(BOOL p0)
<void> SetBlipFlashes(Blip blip, BOOL toggle)
<void> SetBlipFlashesAlternate(Blip blip, BOOL toggle)
<bool> IsBlipFlashing(Blip blip)
<void> SetBlipAsShortRange(Blip blip, BOOL toggle)
<void> SetBlipScale(Blip blip, float scale)
<void> SetBlipPriority(Blip blip, int priority)
<void> SetBlipDisplay(Blip blip, int displayId)
<void> SetBlipCategory(Blip blip, int index)
<void> RemoveBlip(Blip* blip)
<void> SetBlipAsFriendly(Blip blip, BOOL toggle)
<void> PulseBlip(Blip blip)
<void> ShowNumberOnBlip(Blip blip, int number)
<void> HideNumberOnBlip(Blip blip)
<void> 0x75a16c3da34f1245(Blip blip, BOOL p1)
<void> ShowTickOnBlip(Blip blip, BOOL toggle)
<void> ShowHeadingIndicatorOnBlip(Blip blip, BOOL toggle)
<void> SetBlipFriendly(Blip blip, BOOL toggle)
<void> SetBlipFriend(Blip blip, BOOL toggle)
<void> 0xdcfb5d4db8bf367e(Any p0, BOOL p1)
<void> 0xc4278f70131baa6d(Any p0, BOOL p1)
<void> SetBlipShrink(Blip blip, BOOL toggle)
<void> 0x25615540d894b814(Any p0, BOOL p1)
<bool> DoesBlipExist(Blip blip)
<void> SetWaypointOff()
<void> 0xd8e694757bcea8e9()
<void> RefreshWaypoint()
<bool> IsWaypointActive()
<void> SetNewWaypoint(float x, float y)
<void> SetBlipBright(Blip blip, BOOL toggle)
<void> SetBlipShowCone(Blip blip, BOOL toggle)
<void> 0xc594b315edf2d4af(Ped ped)
<any> SetMinimapComponent(int component, BOOL toggle, int componentColor)
<void> 0x60e892ba4f5bdca4()
<blip> GetMainPlayerBlipId()
<void> 0x41350b4fc28e3941(BOOL p0)
<void> HideLoadingOnFadeThisFrame()
<void> SetRadarAsInteriorThisFrame(Hash interior, float x, float y, int heading, int zoom)
<void> SetRadarAsExteriorThisFrame()
<void> SetPlayerBlipPositionThisFrame(float x, float y)
<any> 0x9049fe339d5f6f6f()
<void> DisableRadarThisFrame()
<void> HideCurrentInteriorOnMap()
<void> CenterPlayerOnRadarThisFrame()
<void> SetWidescreenFormat(Any p0)
<void> DisplayAreaName(BOOL toggle)
<void> DisplayCash(BOOL toggle)
<void> UpdateDisplayCash(BOOL toggle)
<void> SetPlayerCashChange(int cash, int bank)
<void> DisplayAmmoThisFrame(BOOL display)
<void> DisplaySniperScopeThisFrame()
<void> HideHudAndRadarThisFrame()
<void> 0xe67c6dfd386ea5e7(BOOL p0)
<void> SetDisplayCash()
<void> RemoveDisplayCash()
<void> SetMultiplayerBankCash()
<void> RemoveMultiplayerBankCash()
<void> SetMultiplayerHudCash(int p0, int p1)
<void> RemoveMultiplayerHudCash()
<void> HideHelpTextThisFrame()
<void> DisplayHelpTextThisFrame(char* message, BOOL p1)
<void> ShowWeaponWheel(BOOL forcedShow)
<void> BlockWeaponWheelThisFrame()
<hash> 0xa48931185f0536fe()
<void> HideWeaponHash(Hash weaponHash)
<any> 0xa13e93403f26c812(Any p0)
<void> 0x14c9fdcc41f81f63(BOOL p0)
<void> SetGpsFlags(int p0, float p1)
<void> ClearGpsFlags()
<void> 0x1eac5f91bcbc5073(BOOL p0)
<void> ClearGpsRaceTrack()
<void> 0xdb34e8d56fc13b08(Any p0, BOOL p1, BOOL p2)
<void> 0x311438a071dd9b1a(float x, float y, float z)
<void> 0x900086f371220b6f(BOOL p0, Any p1, Any p2)
<void> 0xe6de0561d9232a64()
<void> 0x3d3d15af7bcaaf83(Any p0, BOOL p1, BOOL p2)
<void> 0xa905192a6781c41b(float x, float y, float z)
<void> 0x3dda37128dd1aca8(BOOL p0)
<void> 0x67eedea1b9bafd94()
<void> ClearGpsPlayerWaypoint()
<void> SetGpsFlashes(BOOL toggle)
<void> 0x7b21e0bb01e8224a(Any p0)
<void> FlashMinimapDisplay()
<void> 0x6b1de27ee78e6a19(Any p0)
<void> ToggleStealthRadar(BOOL toggle)
<void> KeyHudColour(BOOL p0, Any p1)
<void> SetMissionName(BOOL p0, char* name)
<void> SetMissionName2(BOOL p0, char* name)
<void> 0x817b86108eb94e51(BOOL p0, Any* p1, Any* p2, Any* p3, Any* p4, Any* p5, Any* p6, Any* p7, Any* p8)
<void> SetMinimapBlockWaypoint(BOOL toggle)
<void> SetNorthYanktonMap(BOOL toggle)
<void> SetMinimapRevealed(BOOL toggle)
<float> 0xe0130b41d3cf4574()
<bool> IsMinimapAreaRevealed(float x, float y, float radius)
<void> 0x62e849b7eb28e770(BOOL p0)
<void> 0x0923dbf87dff735e(float x, float y, float z)
<void> SetMinimapGolfCourse(int hole)
<void> 0x35edd5b2e3ff01c0()
<void> LockMinimapAngle(int angle)
<void> UnlockMinimapAngle()
<void> LockMinimapPosition(float x, float y)
<void> UnlockMinimapPosition()
<void> SetMinimapAttitudeIndicatorLevel(float altitude, BOOL p1)
<void> 0x3f5cc444dcaaa8f2(Any p0, Any p1, BOOL p2)
<void> 0x975d66a0bc17064c(Any p0)
<void> 0x06a320535f5f0248(Any p0)
<void> SetRadarBigmapEnabled(BOOL toggleBigMap, BOOL showFullMap)
<bool> IsHudComponentActive(int id)
<bool> IsScriptedHudComponentActive(int id)
<void> HideScriptedHudComponentThisFrame(int id)
<bool> 0x09c0403ed9a751c2(Any p0)
<void> HideHudComponentThisFrame(int id)
<void> ShowHudComponentThisFrame(int id)
<void> 0xa4dede28b1814289()
<void> ResetReticuleValues()
<void> ResetHudComponentValues(int id)
<void> SetHudComponentPosition(int id, float x, float y)
<vector3> GetHudComponentPosition(int id)
<void> ClearReminderMessage()
<bool> GetHudScreenPositionFromWorldPosition(float worldX, float worldY, float worldZ, float* screenX, float* screenY)
<void> DisplayJobReport()
<void> 0xee4c0e6dbc6f2c6f()
<any> 0x9135584d09a3437e()
<bool> IsFloatingHelpTextOnScreen(Any p0)
<void> SetFloatingHelpTextScreenPosition(Any p0, float p1, float p2)
<void> SetFloatingHelpTextWorldPosition(Any p0, float x, float y, float z)
<void> SetFloatingHelpTextToEntity(Any p0, Any p1, float p2, float p3)
<void> SetFloatingHelpTextStyle(Any p0, Any p1, Any p2, Any p3, Any p4, Any p5)
<void> ClearFloatingHelp(Any p0, BOOL p1)
<void> SetMpGamerTagColor(int headDisplayId, char* username, BOOL pointedClanTag, BOOL isRockstarClan, char* clanTag, Any p5, int r, int g, int b)
<bool> IsMpGamerTagMovieActive()
<int> CreateFakeMpGamerTag(Ped ped, char* username, BOOL pointedClanTag, BOOL isRockstarClan, char* clanTag, Any p5)
<void> RemoveMpGamerTag(int gamerTagId)
<bool> IsMpGamerTagActive(int gamerTagId)
<bool> AddTrevorRandomModifier(int gamerTagId)
<void> SetMpGamerTagVisibility(int gamerTagId, int component, BOOL toggle)
<void> SetMpGamerTag(int headDisplayId, BOOL p1)
<void> SetMpGamerTagIcons(int headDisplayId, BOOL p1)
<void> SetMpGamerTagColour(int gamerTagId, int flag, int color)
<void> SetMpGamerTagHealthBarColour(int headDisplayId, int color)
<void> SetMpGamerTagAlpha(int gamerTagId, int component, int alpha)
<void> SetMpGamerTagWantedLevel(int gamerTagId, int wantedlvl)
<void> SetMpGamerTagName(int gamerTagId, char* string)
<bool> HasMpGamerTag2(int gamerTagId)
<void> SetMpGamerTagChatting(int gamerTagId, char* string)
<int> GetActiveWebsiteId()
<int> GetCurrentWebsiteId()
<bool> GetCurrentWebsitePageId(int websiteID)
<void> 0xb99c4e4d9499df29(BOOL p0)
<any> 0xaf42195a42c63bba()
<void> SetWarningMessage(char* entryLine1, int instructionalKey, char* entryLine2, BOOL p3, Any p4, Any* p5, Any* p6, BOOL background)
<void> SetWarningMessageWithHeader(char* entryHeader, char* entryLine1, int instructionalKey, char* entryLine2, BOOL p4, Any p5, Any* p6, Any* p7, BOOL background)
<void> SetWarningMessage3(char* entryHeader, char* entryLine1, Any instructionalKey, char* entryLine2, BOOL p4, Any p5, Any p6, Any* p7, Any* p8, BOOL p9)
<bool> CreateDrawList(Any p0, char* text, Any p2, Any p3, Any p4, Any p5)
<bool> 0xdaf87174be7454ff(Any p0)
<void> 0x6ef54ab721dc6242()
<bool> IsWarningMessageActive()
<void> 0x7792424aa0eac32e()
<void> SetMapFullScreen(BOOL toggle)
<void> 0x1eae6dd17b7a5efa(Any p0)
<any> 0x551df99658db6ee8(float p0, float p1, float p2)
<void> 0x2708fc083123f9ff()
<any> 0x1121bfa1a1a522a8()
<void> 0x82cedc33687e1f50(BOOL p0)
<void> 0x211c4ef450086857()
<void> 0xbf4f34a85ca2970c()
<void> ActivateFrontendMenu(Hash menuhash, BOOL Toggle_Pause, int component)
<void> RestartFrontendMenu(Hash menuHash, int p1)
<hash> GetCurrentFrontendMenu()
<void> SetPauseMenuActive(BOOL toggle)
<void> DisableFrontendThisFrame()
<void> 0xba751764f0821256()
<void> 0xcc3fdded67bcfc63()
<void> SetFrontendActive(BOOL active)
<bool> IsPauseMenuActive()
<any> 0x2f057596f2bd0061()
<int> GetPauseMenuState()
<vector3> 0x5bff36d6ed83e0ae()
<bool> IsPauseMenuRestarting()
<void> LogDebugInfo(char* p0)
<void> 0x77f16b447824da6c(int p0)
<void> 0xcdca26e80faecb8f()
<void> PauseMenuActivateContext(Hash contextHash)
<void> ObjectDecalToggle(Hash contextHash)
<bool> 0x84698ab38d0c6636(Hash hash)
<any> 0x2a25adc48f87841f()
<any> 0xde03620f8703a9df()
<any> 0x359af31a4b52f5ed()
<any> 0x13c4b962653a5280()
<bool> 0xc8e1071177a23be5(Any* p0, Any* p1, Any* p2)
<void> EnableDeathbloodSeethrough(BOOL p0)
<void> 0xc78e239ac5b2ddb9(BOOL p0, Any p1, Any p2)
<void> 0xf06ebb91a81e09e3(BOOL p0)
<any> 0x3bab9a4e4f2ff5c7()
<void> 0xec9264727eec0f28()
<void> 0x14621bb1df14e2b2()
<any> 0x66e7cb63c97b7d20()
<any> 0x593feae1f73392d4()
<any> 0x4e3cd0ef8a489541()
<any> 0xf284ac67940c6812()
<bool> 0x2e22fefa0100275e()
<void> 0x0cf54f20de43879c(Any p0)
<void> 0x36c1451a88a09630(Any* p0, Any* p1)
<void> 0x7e17be53e1aaabaf(int* p0, int* p1, int* p2)
<bool> 0xa238192f33110615(int* p0, int* p1, int* p2)
<bool> SetUseridsUihidden(Any p0, Any* p1)
<bool> 0xca6b2f7ce32ab653(Any p0, Any* p1, Any p2)
<bool> 0x90a6526cf0381030(Any p0, Any* p1, Any p2, Any p3)
<bool> 0x24a49beaf468dc90(Any p0, Any* p1, Any p2, Any p3, Any p4)
<bool> 0x5fbd7095fe7ae57f(Any p0, float* p1)
<bool> 0x8f08017f9d7c47bd(Any p0, Any* p1, Any p2)
<bool> 0x052991e59076e4e4(Hash p0, Any* p1)
<void> ClearPedInPauseMenu()
<void> GivePedToPauseMenu(Ped ped, int p1)
<void> 0x3ca6050692bc61b0(BOOL p0)
<void> 0xecf128344e9ff9f1(BOOL p0)
<void> ShowSocialClubLegalScreen()
<any> 0xf13fe2a80c05c561()
<int> 0x6f72cd94f7b5b68c()
<void> 0x75d3691713c3b05a()
<void> 0xd2b32be3fc1626c6()
<void> 0x9e778248d6685fe0(char* p0)
<bool> IsSocialClubActive()
<void> 0x1185a8087587322c(BOOL p0)
<void> 0x8817605c2ba76200()
<bool> IsTextChatActive()
<void> AbortTextChat()
<void> SetTextChatUnk(BOOL p0)
<void> 0xcef214315d276fd1(BOOL p0)
<void> SetPedAiBlip(int pedHandle, BOOL showViewCones)
<bool> DoesPedHaveAiBlip(Ped ped)
<void> SetAiBlipType(Ped ped, int type)
<void> HideSpecialAbilityLockonOperation(Any p0, BOOL p1)
<void> IsAiBlipAlwaysShown(Ped ped, BOOL flag)
<void> SetAiBlipMaxDistance(Ped ped, float distance)
<blip*> 0x7cd934010e115c2c(Ped ped)
<blip> GetAiBlip(Ped ped)
<any> 0xa277800a9eae340e()
<void> 0x2632482fd6b9ab87()
<void> SetDirectorMode(BOOL toggle)
<void> 0x04655f9d075d0ae5(BOOL p0)
```