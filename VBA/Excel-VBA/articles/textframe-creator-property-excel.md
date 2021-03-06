---
title: TextFrame.Creator Property (Excel)
keywords: vbaxl10.chm643074
f1_keywords:
- vbaxl10.chm643074
ms.prod: excel
api_name:
- Excel.TextFrame.Creator
ms.assetid: 7aa570dc-1a79-40b4-f6ad-ea71dae97110
ms.date: 06/08/2017
---


# TextFrame.Creator Property (Excel)

Returns a 32-bit integer that indicates the application in which this object was created. Read-only  **Long** .


## Syntax

 _expression_ . **Creator**

 _expression_ A variable that represents a **TextFrame** object.


## Remarks

If the object was created in Microsoft Excel, this property returns the string XCEL, which is equivalent to the hexadecimal number 5843454C. The  **Creator** property is designed to be used in Microsoft Excel for the Macintosh, where each application has a four-character creator code. For example, Microsoft Excel has the creator code XCEL.


## See also


#### Concepts


[TextFrame Object](textframe-object-excel.md)

