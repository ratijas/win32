---
Description: Unassociates an attached ID3DXTextureGutterHelper object with the ID3DXPRTBuffer object.
ms.assetid: 0bd8322a-8af1-4173-bbe3-9134c831cf3a
title: ID3DXPRTBuffer::ReleaseGH method
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# ID3DXPRTBuffer::ReleaseGH method

Unassociates an attached [**ID3DXTextureGutterHelper**](id3dxtexturegutterhelper.md) object with the [**ID3DXPRTBuffer**](id3dxprtbuffer.md) object.

## Syntax


```C++
HRESULT ReleaseGH();
```



## Parameters

This method has no parameters.

## Return value

Type: **[**HRESULT**](https://msdn.microsoft.com/windows/desktop/455d07e9-52c3-4efb-a9dc-2955cbfd38cc)**

If the method succeeds, the return value is D3D\_OK.

## Remarks

This method releases the pointer to the [**ID3DXTextureGutterHelper**](id3dxtexturegutterhelper.md) interface.

You must ensure that the number of [**ID3DXPRTBuffer::AttachGH**](id3dxprtbuffer--attachgh.md) calls matches the number of **ID3DXPRTBuffer::ReleaseGH** calls. After calling **ID3DXPRTBuffer::ReleaseGH**, the pGH pointer returned by **ID3DXPRTBuffer::AttachGH** should no longer be used.

## Requirements



|                    |                                                                                        |
|--------------------|----------------------------------------------------------------------------------------|
| Header<br/>  | <dl> <dt>D3DX9Mesh.h</dt> </dl> |
| Library<br/> | <dl> <dt>D3dx9.lib</dt> </dl>   |



## See also

<dl> <dt>

[ID3DXPRTBuffer](id3dxprtbuffer.md)
</dt> <dt>

[**ID3DXPRTBuffer::AttachGH**](id3dxprtbuffer--attachgh.md)
</dt> </dl>

 

 



