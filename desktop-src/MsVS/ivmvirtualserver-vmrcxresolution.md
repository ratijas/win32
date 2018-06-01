---
title: IVMVirtualServer VMRCXResolution property
description: The VMRCXResolution property contains the horizontal resolution used for server administration.
ms.assetid: ea13bed4-dc80-4b41-b9d6-6bc26f4fd67d
keywords:
- VMRCXResolution property Virtual Server
- VMRCXResolution property Virtual Server , IVMVirtualServer interface
- IVMVirtualServer interface Virtual Server , VMRCXResolution property
- VMRCXResolution property Virtual Server , VMVirtualServer class
- VMVirtualServer class Virtual Server , VMRCXResolution property
topic_type:
- apiref
api_name:
- IVMVirtualServer.VMRCXResolution
- IVMVirtualServer.get_VMRCXResolution
- IVMVirtualServer.put_VMRCXResolution
- VMVirtualServer.VMRCXResolution
api_location:
- VsComInterfaces.h
api_type:
- COM
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# IVMVirtualServer::VMRCXResolution property

The **VMRCXResolution** property contains the horizontal resolution used for server administration.

This property is read/write.

## Syntax


```C++
HRESULT put_VMRCXResolution(
  [in]  long vmrcXResolution
);

HRESULT get_VMRCXResolution(
  [out] long *vmrcXResolution
);
```

<span codelanguage="VisualBasic"></span>

<table>
<colgroup>
<col style="width: 100%" />
</colgroup>
<thead>
<tr class="header">
<th>VB</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><pre><code>VMVirtualServer.VMRCXResolution( _
  ByRef vmrcXResolution, _
  ByVal vmrcXResolution _
)</code></pre></td>
</tr>
</tbody>
</table>



## Property value

The horizontal resolution used for server administration.

This property value is read/write.

## Error codes



| Name                                                                                          | Meaning                                                 |
|-----------------------------------------------------------------------------------------------|---------------------------------------------------------|
| <dl> <dt>S\_OK</dt> </dl>              | The operation was successful.<br/>                |
| <dl> <dt>E\_POINTER</dt> </dl>         | The parameter *vmrcXResolution* is **NULL**.<br/> |
| <dl> <dt>DISP\_E\_EXCEPTION</dt> </dl> | An unexpected error occurred.<br/>                |



## Examples

The following example displays the **VMRCXResolution** property value of the [**VMVirtualServer**](ivmvirtualserver.md) object.


```VB
Set objVS = CreateObject("VirtualServer.Application")

Wscript.Echo "Name: " & objVS.Name
Wscript.Echo "VMRC X-Resolution: " & objVS.VMRCXResolution
```



## Requirements



|                     |                                                                                                   |
|---------------------|---------------------------------------------------------------------------------------------------|
| Product<br/>  | Microsoft Virtual Server 2005 onWindows Server 2003<br/>                                    |
| Download<br/> | Microsoft Virtual Server 2005 R2 SP1 Update onWindows Server 2008orWindows Server 2003<br/> |
| Header<br/>   | <dl> <dt>VsComInterfaces.h</dt> </dl>      |



## See also

<dl> <dt>

[**IVMVirtualServer**](ivmvirtualserver.md)
</dt> </dl>

 

 




