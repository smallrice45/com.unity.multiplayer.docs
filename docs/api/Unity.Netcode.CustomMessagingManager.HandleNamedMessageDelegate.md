---  
id: Unity.Netcode.CustomMessagingManager.HandleNamedMessageDelegate  
title: Unity.Netcode.CustomMessagingManager.HandleNamedMessageDelegate  
---

<div class="markdown level0 summary">

Delegate used to handle named messages

</div>

<div class="markdown level0 conceptual">

</div>

##### **Namespace**: System.Dynamic.ExpandoObject

##### **Assembly**: MLAPI.dll

##### Syntax

``` lang-csharp
public delegate void HandleNamedMessageDelegate(ulong senderClientId, FastBufferReader messagePayload);
```

##### Parameters

| Type             | Name             | Description |
|------------------|------------------|-------------|
| System.UInt64    | \*senderClientId |             |
| FastBufferReader | \*messagePayload |             |
