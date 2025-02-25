---
UID: NF:tapi3if.ITDigitDetectionEvent.get_Call
title: ITDigitDetectionEvent::get_Call (tapi3if.h)
description: The get_Call method gets a pointer to the ITCallInfo interface for the call on which the event occurred.helpviewer_keywords: ["ITDigitDetectionEvent interface [TAPI 2.2]","get_Call method","ITDigitDetectionEvent.get_Call","ITDigitDetectionEvent::get_Call","_tapi3_itdigitdetectionevent_get_call","get_Call","get_Call method [TAPI 2.2]","get_Call method [TAPI 2.2]","ITDigitDetectionEvent interface","tapi3.itdigitdetectionevent_get_call","tapi3if/ITDigitDetectionEvent::get_Call"]
old-location: tapi3\itdigitdetectionevent_get_call.htm
tech.root: Tapi
ms.assetid: 98168b0c-132b-47cf-9d5d-6fba7b570216
ms.date: 12/05/2018
ms.keywords: ITDigitDetectionEvent interface [TAPI 2.2],get_Call method, ITDigitDetectionEvent.get_Call, ITDigitDetectionEvent::get_Call, _tapi3_itdigitdetectionevent_get_call, get_Call, get_Call method [TAPI 2.2], get_Call method [TAPI 2.2],ITDigitDetectionEvent interface, tapi3.itdigitdetectionevent_get_call, tapi3if/ITDigitDetectionEvent::get_Call
f1_keywords:
- tapi3if/ITDigitDetectionEvent.get_Call
dev_langs:
- c++
req.header: tapi3if.h
req.include-header: Tapi3.h
req.target-type: Windows
req.target-min-winverclnt: 
req.target-min-winversvr: 
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Uuid.lib
req.dll: Tapi3.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- Tapi3.dll
api_name:
- ITDigitDetectionEvent.get_Call
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# ITDigitDetectionEvent::get_Call


## -description


The 
<b>get_Call</b> method gets a pointer to the 
<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-itcallinfo">ITCallInfo</a> interface for the call on which the event occurred.


## -parameters




### -param ppCallInfo [out]

Pointer to 
<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-itcallinfo">ITCallInfo</a> interface.


## -returns



This method can return one of these values.

<table>
<tr>
<th>Value</th>
<th>Meaning</th>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>S_OK</b></dt>
</dl>
</td>
<td width="60%">
Method succeeded.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_OUTOFMEMORY</b></dt>
</dl>
</td>
<td width="60%">
Insufficient memory exists to perform the operation.

</td>
</tr>
<tr>
<td width="40%">
<dl>
<dt><b>E_POINTER</b></dt>
</dl>
</td>
<td width="60%">
The <i>ppCallInfo</i> parameter is not a valid pointer.

</td>
</tr>
</table>
 




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/tapi3if/nn-tapi3if-itdigitdetectionevent">ITDigitDetectionEvent</a>
 

 

