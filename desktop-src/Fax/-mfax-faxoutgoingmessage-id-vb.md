---
Description: The Id property is a null-terminated string that contains a unique identifier for the outbound fax message.
ms.assetid: 00e1687b-be86-417b-a0cd-8eb3a67a4bae
title: FaxOutgoingMessage.Id property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# FaxOutgoingMessage.Id property

The **Id** property is a null-terminated string that contains a unique identifier for the outbound fax message.

This property is read-only.

## Syntax


```VB
Property Id As String
```



## Property value

A **String** that receives a unique ID for the outbound fax message. This is the same ID that the fax job had when the job was active.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows XP \[desktop apps only\]<br/>                                             |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                    |
| Header<br/>                   | <dl> <dt>FaxComex.h</dt> </dl>   |
| DLL<br/>                      | <dl> <dt>Fxscomex.dll</dt> </dl> |



## See also

<dl> <dt>

[Visual Basic Example](-mfax-opening-a-fax-from-the-outgoing-archive.md)
</dt> <dt>

[**FaxOutgoingMessage**](-mfax-faxoutgoingmessage.md)
</dt> <dt>

[**IFaxOutgoingMessage**](/previous-versions/windows/desktop/api/FaxComex/nn-faxcomex-ifaxoutgoingmessage)
</dt> </dl>

 

 



