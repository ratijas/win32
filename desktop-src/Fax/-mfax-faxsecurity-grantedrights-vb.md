---
Description: The GrantedRights property is a combination of the fax server access rights granted to the user referencing this property.
ms.assetid: 7fd4d1c0-3980-410a-8150-34461cbff59c
title: FaxSecurity.GrantedRights property
ms.technology: desktop
ms.prod: windows
ms.author: windowssdkdev
ms.topic: article
ms.date: 05/31/2018
---

# FaxSecurity.GrantedRights property

The **GrantedRights** property is a combination of the fax server access rights granted to the user referencing this property. For example, some users have permission to submit fax jobs with high priority while others have permission to submit jobs with normal or low priority only.

This property is read-only.

## Syntax


```VB
Property GrantedRights As Integer
```



## Property value

A variable of type [**FAX\_ACCESS\_RIGHTS\_ENUM**](/previous-versions/windows/desktop/api/FaxComex/ne-faxcomex-fax_access_rights_enum) that receives the bitwise combination of access rights granted to the user. For possible values, see **FAX\_ACCESS\_RIGHTS\_ENUM**.

## Remarks

The **GrantedRights** property reflects rights granted by the fax server, while the [**Descriptor**](/previous-versions/windows/desktop/api/FaxComex/nf-faxcomex-ifaxsecurity-get_descriptor) property represents the security descriptor, which contains the rights explicitly granted to a user by the fax administrator.

To read this property, a user must have the [****farQUERY\_CONFIG****](/previous-versions/windows/desktop/api/FaxComex/ne-faxcomex-fax_access_rights_enum) access right.

## Requirements



|                                     |                                                                                         |
|-------------------------------------|-----------------------------------------------------------------------------------------|
| Minimum supported client<br/> | Windows XP \[desktop apps only\]<br/>                                             |
| Minimum supported server<br/> | Windows Server 2003 \[desktop apps only\]<br/>                                    |
| Header<br/>                   | <dl> <dt>FaxComex.h</dt> </dl>   |
| DLL<br/>                      | <dl> <dt>Fxscomex.dll</dt> </dl> |



## See also

<dl> <dt>

[**FaxSecurity**](-mfax-faxsecurity.md)
</dt> <dt>

[**IFaxSecurity**](/previous-versions/windows/desktop/api/FaxComex/nn-faxcomex-ifaxsecurity)
</dt> </dl>

 

 



