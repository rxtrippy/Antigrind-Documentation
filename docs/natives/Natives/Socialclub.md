---
sidebar_position: 28
---

# SocialClub

```lua
<int> GetTotalScInboxIds()
<hash> ScInboxMessageInit(int p0)
<bool> IsScInboxValid(int p0)
<bool> ScInboxMessagePop(int p0)
<bool> ScInboxMessageGetDataInt(int p0, char* context, int* out)
<bool> ScInboxMessageGetDataBool(int p0, char* p1)
<bool> ScInboxMessageGetDataString(int p0, char* context, char* out)
<bool> ScInboxMessagePush(int p0)
<char*> ScInboxMessageGetString(int p0)
<void> 0xda024bdbd600f44a(int* networkHandle)
<void> CreatePresenceStatUpdate(char* p0)
<bool> ScInboxMessageGetUgcdata(Any p0, Any* p1)
<bool> CreatePresenceBounty(char* playerName)
<bool> 0x87e0052f08bd64e6(Any p0, int* p1)
<void> ScInboxGetEmails(int offset, int limit)
<any> 0x16da8172459434aa()
<bool> 0x4737980e8a283806(int p0, Any* p1)
<void> 0x44aca259d67651db(Any* p0, Any p1)
<void> ScEmailMessagePushGamerToRecipList(Player* player)
<void> ScEmailMessageClearRecipList()
<void> 0x116fb94dc4b79f17(char* p0)
<void> 0xbfa0a56a817c6c7d(BOOL p0)
<bool> 0xbc1cc91205ec8d6e()
<char*> 0xdf649c4e9afdd788()
<bool> 0x1f1e9682483697c7(Any p0, Any p1)
<bool> 0x287f1f75d2803595(Any p0, Any* p1)
<bool> 0x487912fd248efddf(Any p0, float p1)
<bool> 0x8416fe4e4629d7d7(char* p0)
<bool> ScStartCheckStringTask(char* string, int* taskHandle)
<bool> ScHasCheckStringTaskCompleted(int taskHandle)
<int> ScGetCheckStringStatus(int taskHandle)
<any> 0x85535acf97fc0969(Any p0)
<int> 0x930de22f07b1cce3(Any p0)
<bool> 0xf6baaaf762e1bf40(char* p0, int* p1)
<bool> 0xf22ca0fd74b80e7a(Any p0)
<any> 0x9237e334f6e43156(Any p0)
<any> 0x700569dba175a77c(Any p0)
<any> 0x1d4446a62d35b0d0(Any p0, Any p1)
<any> 0x2e89990ddff670c3(Any p0, Any p1)
<bool> 0xd0ee05fe193646ea(Any* p0, Any* p1, Any* p2)
<bool> 0x1989c6e6f67e76a8(Any* p0, Any* p1, Any* p2)
<any> 0x07c61676e5bb52cd(Any p0)
<any> 0x8147fff6a718e1ad(Any p0)
<bool> 0x0f73393bac7e6730(Any* p0, int* p1)
<any> 0xd302e99edf0449cf(Any p0)
<any> 0x5c4ebffa98bdb41c(Any p0)
<any> 0xff8f3a92b75ed67a()
<any> 0x4a7d6e727f941747(Any* p0)
<bool> 0x8cc469ab4d349b7c(int p0, char* p1, Any* p2)
<bool> 0x699e4a5c8c893a18(int p0, char* p1, Any* p2)
<bool> 0x19853b5b17d77bca(Any p0, Any* p1)
<bool> 0x6bfb12ce158e3dd4(Any p0)
<bool> 0xfe4c1d0d3b9cc17e(Any p0, Any p1)
<any> 0xd8122c407663b995()
<bool> 0x3001bef2feca3680()
<bool> 0x92da6e70ef249bd1(char* p0, int* p1)
<void> 0x675721c9f644d161()
<char*> ScGetNickname()
<bool> 0x225798743970412b(int* p0)
<bool> 0x418dc16fae452c1c(int p0)
```