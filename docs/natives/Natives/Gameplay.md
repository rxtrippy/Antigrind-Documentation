---
sidebar_position: 15
---

# Gameplay

```lua
<int> GetAllocatedStackSize()
<int> GetFreeStackSlotsCount(int threadId)
<void> SetRandomSeed(int time)
<void> SetTimeScale(float time)
<void> SetMissionFlag(BOOL setToTrueOrNot)
<bool> GetMissionFlag()
<void> SetRandomEventFlag(BOOL setToTrueOrNot)
<bool> GetRandomEventFlag()
<char*> GetGlobalCharBuffer()
<void> 0x4dcdf92bf64236cd(char* p0, char* p1)
<void> 0x31125fd509d9043f(Any* p0)
<void> 0xebd3205a207939ed(Any* p0)
<void> 0x97e7e2c04245115b(Any p0)
<void> 0xeb078ca2b5e82add(Any p0, Any p1)
<void> 0x703cc7f60cbb2b57(Any p0)
<void> 0x8951eb9c6906d3c8()
<void> 0xba4b8d83bdc75551(Any p0)
<bool> 0xe8b9c0ec9e183f35()
<void> 0x65d2ebb47e1cec21(BOOL p0)
<void> 0x6f2135b6129620c1(BOOL p0)
<void> 0x8d74e26f54b4e5c3(char* p0)
<bool> 0xb335f761606db47c(Any* p1, Any* p2, Any p3, BOOL p4)
<hash> GetPrevWeatherTypeHashName()
<hash> GetNextWeatherTypeHashName()
<bool> IsPrevWeatherType(char* weatherType)
<bool> IsNextWeatherType(char* weatherType)
<void> SetWeatherTypePersist(char* weatherType)
<void> SetWeatherTypeNowPersist(char* weatherType)
<void> SetWeatherTypeNow(char* weatherType)
<void> SetWeatherTypeOverTime(char* weatherType, float time)
<void> SetRandomWeatherType()
<void> ClearWeatherTypePersist()
<void> GetWeatherTypeTransition(Any p1, Any p2, Any p3)
<void> SetWeatherTypeTransition(Any p1, Any p2, Any p3)
<void> SetOverrideWeather(char* weatherType)
<void> ClearOverrideWeather()
<void> 0xb8f87ead7533b176(float p0)
<void> 0xc3ead29ab273ece8(float p0)
<void> 0xa7a1127490312c36(float p0)
<void> 0x31727907b2c43c55(float p0)
<void> 0x405591ec8fd9096d(float p0)
<void> 0xf751b16fb32abc1d(float p0)
<void> 0xb3e6360dde733e82(float p0)
<void> 0x7c9c0b1eeb1f9072(float p0)
<void> 0x6216b116083a7cb4(float p0)
<void> 0x9f5e6bb6b34540da(float p0)
<void> 0xb9854dfde0d833d6(float p0)
<void> SetNearbyWaveHeight(float p0)
<void> 0xa8434f1dff41d6e7(float p0)
<void> 0xc3c221addde31a11(float p0)
<void> SetWind(float speed)
<void> SetWindSpeed(float speed)
<float> GetWindSpeed()
<void> SetWindDirection(float direction)
<vector3> GetWindDirection()
<void> SetRainFxIntensity(float intensity)
<float> GetRainLevel()
<float> GetSnowLevel()
<void> ForceLightningFlash()
<void> 0x02deaac8f8ea7fe7(char* p0)
<void> PreloadCloudHat(char* name)
<void> LoadCloudHat(char* name, float transitionTime)
<void> UnloadCloudHat(char* name, float p1)
<void> ClearCloudHat()
<void> SetCloudHatOpacity(float opacity)
<float> GetCloudHatOpacity()
<int> GetGameTimer()
<float> GetFrameTime()
<float> GetBenchmarkTime()
<int> GetFrameCount()
<float> GetRandomFloatInRange(float startRange, float endRange)
<int> GetRandomIntInRange(int startRange, int endRange)
<bool> GetGroundZFor3dCoord(float x, float y, float z, float* groundZ, BOOL ignoreWater)
<bool> GetGroundZAndNormalFor3dCoord(float x, float y, float z, float* groundZ, Vector3* offsets)
<float> Asin(float p0)
<float> Acos(float p0)
<float> Tan(float p0)
<float> Atan(float p0)
<float> Atan2(float p0, float p1)
<float> GetDistanceBetweenCoords(float x1, float y1, float z1, float x2, float y2, float z2, BOOL useZ)
<float> GetAngleBetween2dVectors(float x1, float y1, float x2, float y2)
<float> GetHeadingFromVector2d(float dx, float dy)
<float> 0x7f8f6405f4777af6(float p0, float p1, float p2, float p3, float p4, float p5, float p6, float p7, float p8, BOOL p9)
<vector3> 0x21c235bc64831e5a(float p0, float p1, float p2, float p3, float p4, float p5, float p6, float p7, float p8, BOOL p9)
<bool> 0xf56dfb7b61be7276(float p0, float p1, float p2, float p3, float p4, float p5, float p6, float p7, float p8, float p9, float p10, float p11, Any* p12)
<void> SetBit(int* address, int offset)
<void> ClearBit(int* address, int offset)
<hash> GetHashKey(char* string)
<void> 0xf2f6a2fa49278625(float p0, float p1, float p2, float p3, float p4, float p5, float p6, float p7, float p8, Any* p9, Any* p10, Any* p11, Any* p12)
<bool> IsAreaOccupied(float p0, float p1, float p2, float p3, float p4, float p5, BOOL p6, BOOL p7, BOOL p8, BOOL p9, BOOL p10, Any p11, BOOL p12)
<bool> IsPositionOccupied(float x, float y, float z, float range, BOOL p4, BOOL p5, BOOL p6, BOOL p7, BOOL p8, Any p9, BOOL p10)
<bool> IsPointObscuredByAMissionEntity(float p0, float p1, float p2, float p3, float p4, float p5, Any p6)
<void> ClearArea(float X, float Y, float Z, float radius, BOOL p4, BOOL ignoreCopCars, BOOL ignoreObjects, BOOL p7)
<void> ClearAreaOfEverything(float x, float y, float z, float radius, BOOL p4, BOOL p5, BOOL p6, BOOL p7)
<void> ClearAreaOfVehicles(float x, float y, float z, float radius, BOOL p4, BOOL p5, BOOL p6, BOOL p7, BOOL p8)
<void> ClearAngledAreaOfVehicles(float p0, float p1, float p2, float p3, float p4, float p5, float p6, BOOL p7, BOOL p8, BOOL p9, BOOL p10, BOOL p11)
<void> ClearAreaOfObjects(float x, float y, float z, float radius, int flags)
<void> ClearAreaOfPeds(float x, float y, float z, float radius, int flags)
<void> ClearAreaOfCops(float x, float y, float z, float radius, int flags)
<void> ClearAreaOfProjectiles(float x, float y, float z, float radius, BOOL isNetworkGame)
<void> 0x7ec6f9a478a6a512()
<void> SetSaveMenuActive(BOOL openSaveMenu)
<int> 0x397baa01068baa96()
<void> SetCreditsActive(BOOL toggle)
<void> 0xb51b9ab9ef81868c(BOOL toggle)
<bool> HaveCreditsReachedEnd()
<void> TerminateAllScriptsWithThisName(char* scriptName)
<void> NetworkSetScriptIsSafeForNetworkGame()
<int> AddHospitalRestart(float x, float y, float z, float heading, int hospitalId)
<void> DisableHospitalRestart(int hospitalIndex, BOOL toggle)
<any> AddPoliceRestart(float p0, float p1, float p2, float p3, Any p4)
<void> DisablePoliceRestart(int policeIndex, BOOL toggle)
<void> SetCustomRespawnPosition(float x, float y, float z, float heading)
<void> SetNextRespawnToCustom()
<void> DisableAutomaticRespawn(BOOL disableRespawn)
<void> IgnoreNextRestart(BOOL toggle)
<void> SetFadeOutAfterDeath(BOOL toggle)
<void> SetFadeOutAfterArrest(BOOL toggle)
<void> SetFadeInAfterDeathArrest(BOOL toggle)
<void> SetFadeInAfterLoad(BOOL toggle)
<any> RegisterSaveHouse(float p0, float p1, float p2, float p3, Any* p4, Any p5, Any p6)
<void> SetSaveHouse(int index, BOOL p1, BOOL p2)
<bool> OverrideSaveHouse(BOOL p0, float p1, float p2, float p3, float p4, BOOL p5, float p6, float p7)
<any> 0xa4a0065e39c9f25c(Any p0, Any p1, Any p2, Any p3)
<void> DoAutoSave()
<any> 0x6e04f06094c87047()
<bool> IsAutoSaveInProgress()
<any> 0x2107a3773771186d()
<void> 0x06462a961e94b67c()
<void> BeginReplayStats(Any p0, Any p1)
<void> AddReplayStatValue(Any value)
<void> EndReplayStats()
<any> 0xd642319c54aadeb6()
<any> 0x5b1f2e327b6b6fe1()
<any> 0x2b626a0150e4d449()
<any> 0xdc9274a7ef6b2867()
<any> 0x8098c8d6597aae18(Any p0)
<void> ClearReplayStats()
<any> 0x72de52178c291cb5()
<any> 0x44a0bdc559b35f6e()
<any> 0xeb2104e905c6f2e9()
<any> 0x2b5e102e4a42f2bf()
<bool> IsMemoryCardInUse()
<void> ShootSingleBulletBetweenCoords(float x1, float y1, float z1, float x2, float y2, float z2, int damage, BOOL p7, Hash weaponHash, Ped ownerPed, BOOL isAudible, BOOL isInvisible, float speed)
<void> ShootSingleBulletBetweenCoordsPresetParams(float x1, float y1, float z1, float x2, float y2, float z2, int damage, BOOL p7, Hash weaponHash, Ped ownerPed, BOOL isAudible, BOOL isInvisible, float speed, Entity entity)
<void> ShootSingleBulletBetweenCoordsIgnoreEntityNew(float x1, float y1, float z1, float x2, float y2, float z2, int damage, BOOL p7, Hash weaponHash, Ped ownerPed, BOOL isAudible, BOOL isInvisible, float speed, Entity entity, BOOL p14, BOOL p15, BOOL p16, BOOL p17)
<void> GetModelDimensions(Hash modelHash, Vector3* minimum, Vector3* maximum)
<void> SetFakeWantedLevel(int fakeWantedLevel)
<int> GetFakeWantedLevel()
<bool> IsBitSet(int* address, int offset)
<void> UsingMissionCreator(BOOL toggle)
<void> 0xdea36202fc3382df(BOOL p0)
<void> SetMinigameInProgress(BOOL toggle)
<bool> IsMinigameInProgress()
<bool> IsThisAMinigameScript()
<bool> IsSniperInverted()
<bool> 0xd3d15555431ab793()
<int> GetProfileSetting(int profileSetting)
<bool> AreStringsEqual(char* string1, char* string2)
<int> CompareStrings(char* str1, char* str2, BOOL matchCase, int maxLength)
<int> Absi(int value)
<float> Absf(float value)
<bool> IsSniperBulletInArea(float x1, float y1, float z1, float x2, float y2, float z2)
<bool> IsProjectileInArea(float x1, float y1, float z1, float x2, float y2, float z2, BOOL ownedByPlayer)
<bool> IsProjectileTypeInArea(float x1, float y1, float z1, float x2, float y2, float z2, int type, BOOL p7)
<bool> IsProjectileTypeInAngledArea(float p0, float p1, float p2, float p3, float p4, float p5, float p6, Any p7, BOOL p8)
<bool> IsProjectileTypeWithinDistance(float x, float y, float z, Hash projHash, float radius, BOOL ownedByPlayer)
<bool> GetIsProjectileTypeInArea(float x1, float y1, float z1, float x2, float y2, float z2, Hash projHash, Vector3* projPos, BOOL ownedByPlayer)
<bool> GetProjectileNearPedCoords(Ped ped, Hash projHash, float radius, Vector3* projPos, BOOL ownedByPlayer)
<bool> GetProjectileNearPed(Ped ped, Hash projHash, float radius, Vector3* projPos, Entity* projEnt, BOOL ownedByPlayer)
<bool> IsBulletInAngledArea(float p0, float p1, float p2, float p3, float p4, float p5, float p6, BOOL p7)
<bool> IsBulletInArea(float p0, float p1, float p2, float p3, BOOL p4)
<bool> IsBulletInBox(float p0, float p1, float p2, float p3, float p4, float p5, BOOL p6)
<bool> HasBulletImpactedInArea(float x, float y, float z, float p3, BOOL p4, BOOL p5)
<bool> HasBulletImpactedInBox(float p0, float p1, float p2, float p3, float p4, float p5, BOOL p6, BOOL p7)
<bool> IsOrbisVersion()
<bool> IsDurangoVersion()
<bool> IsXbox360Version()
<bool> IsPs3Version()
<bool> IsPcVersion()
<bool> IsAussieVersion()
<bool> IsStringNull(char* string)
<bool> IsStringNullOrEmpty(char* string)
<bool> StringToInt(char* string, int* outInteger)
<void> SetBitsInRange(int* var, int rangeStart, int rangeEnd, int p3)
<int> GetBitsInRange(int var, int rangeStart, int rangeEnd)
<int> AddStuntJump(float p0, float p1, float p2, float p3, float p4, float p5, float p6, float p7, float p8, float p9, float p10, float p11, float p12, float p13, float p14, Any p15, Any p16)
<int> AddStuntJumpAngled(float p0, float p1, float p2, float p3, float p4, float p5, float p6, float p7, float p8, float p9, float p10, float p11, float p12, float p13, float p14, float p15, float p16, Any p17, Any p18)
<void> DeleteStuntJump(int player)
<void> EnableStuntJumpSet(int p0)
<void> DisableStuntJumpSet(int p0)
<void> EnableAllStuntjumpSets(BOOL p0)
<bool> IsStuntJumpInProgress()
<bool> IsStuntJumpMessageShowing()
<int> 0x996dd1e1e02f1008()
<int> 0x6856ec3d35c81ea4()
<void> CancelStuntJump()
<void> SetGamePaused(BOOL toggle)
<void> SetThisScriptCanBePaused(BOOL toggle)
<void> SetThisScriptCanRemoveBlipsCreatedByAnyScript(BOOL toggle)
<bool> HasButtonCombinationJustBeenEntered(Hash hash, int amount)
<bool> HasCheatStringJustBeenEntered(Hash hash)
<void> UseFreemodeMapBehavior(BOOL toggle)
<void> SetUnkMapFlag(int flag)
<bool> IsFrontendFading()
<void> PopulateNow()
<int> GetIndexOfCurrentLevel()
<void> SetGravityLevel(int level)
<void> StartSaveData(Any* p0, Any p1, BOOL p2)
<void> StopSaveData()
<int> 0xa09f896ce912481f(BOOL p0)
<void> RegisterIntToSave(Any* p0, char* name)
<void> 0xa735353c77334ea0(Any* p0, Any* p1)
<void> RegisterEnumToSave(Any* p0, char* name)
<void> RegisterFloatToSave(Any* p0, char* name)
<void> RegisterBoolToSave(Any* p0, char* name)
<void> RegisterTextLabelToSave(Any* p0, char* name)
<void> 0x6f7794f28c6b2535(Any* p0, char* name)
<void> 0x48f069265a0e4bec(Any* p0, char* name)
<void> 0x8269816f6cfd40f8(Any* p0, char* name)
<void> 0xfaa457ef263e8763(Any* p0, char* name)
<void> StartSaveStruct(Any* p0, int p1, char* structName)
<void> StopSaveStruct()
<void> StartSaveArray(Any* p0, int p1, char* arrayName)
<void> StopSaveArray()
<void> EnableDispatchService(int dispatchType, BOOL toggle)
<void> BlockDispatchServiceResourceCreation(int dispatchType, BOOL toggle)
<int> GetNumberOfDispatchedUnitsForPlayer(int dispatchService)
<bool> CreateIncident(int incidentType, float x, float y, float z, int p5, float radius, int* outIncidentID)
<bool> CreateIncidentWithEntity(int incidentType, Ped ped, int amountOfPeople, float radius, int* outIncidentID)
<void> DeleteIncident(int incidentId)
<bool> IsIncidentValid(int incidentId)
<void> 0xb08b85d860e7ba3c(Any p0, Any p1, Any p2)
<void> 0xd261ba3e7e998072(Any p0, float p1)
<bool> FindSpawnPointInDirection(float x1, float y1, float z1, float x2, float y2, float z2, float distance, Vector3* spawnPoint)
<any> 0x67f6413d3220e18d(Any p0, Any p1, Any p2, Any p3, Any p4, Any p5, Any p6, Any p7, Any p8)
<bool> 0x1327e2fe9746baee(Any p0)
<void> 0xb129e447a2eda4bf(Any p0, BOOL p1)
<any> 0x32c7a7e8c43a1f80(float p0, float p1, float p2, float p3, float p4, float p5, BOOL p6, BOOL p7)
<void> 0xe6869becdd8f2403(Any p0, BOOL p1)
<void> EnableTennisMode(Ped ped, BOOL toggle, BOOL p2)
<bool> IsTennisMode(Ped ped)
<void> 0xe266ed23311f24d4(Any p0, Any* p1, Any* p2, float p3, float p4, BOOL p5)
<bool> 0x17df68d720aa77f8(Any p0)
<bool> 0x19bfed045c647c49(Any p0)
<bool> 0xe95b0c7d5ba3b96b(Any p0)
<void> 0x8fa9c42fc5d7c64b(Any p0, Any p1, float p2, float p3, float p4, BOOL p5)
<void> 0x54f157e0336a3822(Any p0, char* p1, float p2)
<void> 0xd10f442036302d50(Any p0, Any p1, Any p2)
<void> ResetDispatchIdealSpawnDistance()
<void> SetDispatchIdealSpawnDistance(float p0)
<void> SetDispatchTimeBetweenSpawnAttempts(Any p0, float p1)
<void> SetDispatchTimeBetweenSpawnAttemptsMultiplier(Any p0, float p1)
<any> 0x918c7b2d2ff3928b(float p0, float p1, float p2, float p3, float p4, float p5, float p6)
<any> 0x2d4259f1feb81da9(float p0, float p1, float p2, float p3)
<void> RemoveDispatchSpawnBlockingArea(Any p0)
<void> ResetDispatchSpawnBlockingAreas()
<void> 0xd9f692d349249528()
<void> 0xe532ec1a63231b4f(Any p0, Any p1)
<void> 0xb8721407ee9c3ff6(Any p0, Any p1, Any p2)
<void> 0xb3cd58cca6cda852()
<void> 0x2587a48bc88dfadf(BOOL p0)
<void> DisplayOnscreenKeyboard2(int p0, char* windowTitle, Any* p2, Player* defaultText, char* defaultConcat1, char* defaultConcat2, char* defaultConcat3, char* defaultConcat4, char* defaultConcat5, char* defaultConcat6, char* defaultConcat7, int maxInputLength)
<void> DisplayOnscreenKeyboard(int p0, char* windowTitle, char* p2, char* defaultText, char* defaultConcat1, char* defaultConcat2, char* defaultConcat3, int maxInputLength)
<int> UpdateOnscreenKeyboard()
<char*> GetOnscreenKeyboardResult()
<void> SaveNextKeyboardInput(int p0)
<void> RemoveStealthKill(Hash hash, BOOL p1)
<void> 0x1eae0a6e978894a2(int p0, BOOL p1)
<void> SetExplosiveAmmoThisFrame(Player player)
<void> SetFireAmmoThisFrame(Player player)
<void> SetExplosiveMeleeThisFrame(Player player)
<void> SetSuperJumpThisFrame(Player player)
<bool> 0x6fddf453c0c756ec()
<void> 0xfb00ca71da386228()
<any> 0x5aa3befa29f03ad4()
<void> 0xe3d969d2785ffb5e()
<void> ResetLocalplayerState()
<void> 0x0a60017f841a54f2(Any p0, Any p1, Any p2, Any p3)
<void> 0x1ff6bf9a63e5757f()
<void> 0x1bb299305c3e8c13(Any p0, Any p1, Any p2, Any p3)
<bool> 0x8ef5573a1f801a5c(Any p0, Any* p1, Any* p2)
<void> StartBenchmarkTest()
<void> 0xc7db36c24634f52b()
<void> 0x437138b6a830166a()
<void> 0x37deb0aa183fb6d8()
<any> 0xea2f2061875eed90()
<any> 0x3bbbd13e5041a79e()
<bool> 0xa049a5be0f04f2f8()
<any> 0x4750fc27570311ec()
<any> 0x1b2366c3f2a5c8df()
<void> ForceSocialClubUpdate()
<bool> HasAllChunksOnHdd()
<void> CleanupAsyncInstall()
<bool> 0x684a41975f077262()
<any> 0xabb2fa71c83a1b72()
<void> SetShowPedInPauseMenu(BOOL toggle)
<bool> GetShowPedInPauseMenu()
<void> 0x9d8d44adbba61ef2(BOOL p0)
<void> 0x23227df0b2115469()
<any> 0xd10282b6e3751ba0()
```