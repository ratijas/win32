---
title: WOM\_DONE message
description: The WOM\_DONE message is sent to a waveform-audio output callback function when the given output buffer is being returned to the application.
ms.assetid: bbdebb68-82e5-4963-90bb-f93f8a91a8cf
keywords:
- WOM_DONE message Windows Multimedia
topic_type:
- apiref
api_name:
- WOM_DONE
api_location:
- Mmsystem.h
api_type:
- HeaderDef
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# WOM\_DONE message

The **WOM\_DONE** message is sent to a waveform-audio output callback function when the given output buffer is being returned to the application. Buffers are returned to the application when they have been played, or as the result of a call to the [**waveOutReset**](https://www.bing.com/search?q=**waveOutReset**) function.


```C++
WOM_DONE 
dwParam1 = (DWORD) lpwvhdr 
dwParam2 = reserved 
```



## Parameters

<dl> <dt>

<span id="dwParam1"></span><span id="dwparam1"></span><span id="DWPARAM1"></span>*dwParam1*
</dt> <dd>

Pointer to a [**WAVEHDR**](https://www.bing.com/search?q=**WAVEHDR**) structure identifying the buffer.

</dd> <dt>

<span id="dwParam2"></span><span id="dwparam2"></span><span id="DWPARAM2"></span>*dwParam2*
</dt> <dd>

Reserved; must be zero.

</dd> </dl>

## Return Value

This message does not return a value.

## Requirements



|                                     |                                                                                                           |
|-------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows 2000 Professional \[desktop apps only\]<br/>                                                |
| Minimum supported server<br/> | Windows 2000 Server \[desktop apps only\]<br/>                                                      |
| Header<br/>                   | <dl> <dt>Mmsystem.h (include Windows.h)</dt> </dl> |



## See also

<dl> <dt>

[Waveform Audio](waveform-audio.md)
</dt> <dt>

[Waveform Messages](waveform-messages.md)
</dt> </dl>

 

 




