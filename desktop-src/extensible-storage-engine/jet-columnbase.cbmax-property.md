---
title: JET_COLUMNBASE.cbMax property 
TOCTitle: 'cbMax property '
ms:assetid: P:Microsoft.Isam.Esent.Interop.JET_COLUMNBASE.cbMax
ms:mtpsurl: https://msdn.microsoft.com/library/microsoft.isam.esent.interop.jet_columnbase.cbmax(v=EXCHG.10)
ms:contentKeyID: 55103464
ms.date: 07/30/2014
ms.topic: reference
f1_keywords:
- Microsoft.Isam.Esent.Interop.JET_COLUMNBASE.cbMax
dev_langs:
- CSharp
- JScript
- VB
- other
api_name: 
- Microsoft.Isam.Esent.Interop.JET_COLUMNBASE.set_cbMax
- Microsoft.Isam.Esent.Interop.JET_COLUMNBASE.get_cbMax
- Microsoft.Isam.Esent.Interop.JET_COLUMNBASE.cbMax
topic_type: 
- kbSyntax
- apiref
api_type: 
- Managed
api_location: 
- Microsoft.Isam.Esent.Interop.dll
ROBOTS: INDEX,FOLLOW

---

# JET_COLUMNBASE.cbMax property

Gets the maximum length of the column. This is only meaningful for columns of type [Text](hh577895\(v=exchg.10\).md), [LongText](hh577895\(v=exchg.10\).md), [Binary](hh577895\(v=exchg.10\).md) and [LongBinary](hh577895\(v=exchg.10\).md).

**Namespace:**  [Microsoft.Isam.Esent.Interop](hh596136\(v=exchg.10\).md)  
**Assembly:**  Microsoft.Isam.Esent.Interop (in Microsoft.Isam.Esent.Interop.dll)

## Syntax

``` vb
'Declaration
Public Property cbMax As Integer
    Get
    Friend Set
'Usage
Dim instance As JET_COLUMNBASE
Dim value As Integer

value = instance.cbMax
```

``` csharp
public int cbMax { get; internal set; }
```

#### Property value

Type: [System.Int32](/dotnet/api/system.int32)  

## See also

#### Reference

[JET_COLUMNBASE class](dn335045\(v=exchg.10\).md)

[JET_COLUMNBASE members](dn335046\(v=exchg.10\).md)

[Microsoft.Isam.Esent.Interop namespace](hh596136\(v=exchg.10\).md)