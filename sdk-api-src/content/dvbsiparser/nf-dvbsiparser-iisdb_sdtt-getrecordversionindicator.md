---
UID: NF:dvbsiparser.IISDB_SDTT.GetRecordVersionIndicator
title: IISDB_SDTT::GetRecordVersionIndicator (dvbsiparser.h)
description: Receives the version indicator from a record in an Integrated Services Digital Broadcasting (ISDB) software download trigger table (SDTT).helpviewer_keywords: ["GetRecordVersionIndicator","GetRecordVersionIndicator method [Microsoft TV Technologies]","GetRecordVersionIndicator method [Microsoft TV Technologies]","IISDB_SDTT interface","IISDB_SDTT interface [Microsoft TV Technologies]","GetRecordVersionIndicator method","IISDB_SDTT.GetRecordVersionIndicator","IISDB_SDTT::GetRecordVersionIndicator","dvbsiparser/IISDB_SDTT::GetRecordVersionIndicator","mstv.iisdb_sdtt_getrecordversionindicator"]
old-location: mstv\iisdb_sdtt_getrecordversionindicator.htm
tech.root: mstv
ms.assetid: 3b4b4b4b-84b3-4181-bc84-389e72b66053
ms.date: 12/05/2018
ms.keywords: GetRecordVersionIndicator, GetRecordVersionIndicator method [Microsoft TV Technologies], GetRecordVersionIndicator method [Microsoft TV Technologies],IISDB_SDTT interface, IISDB_SDTT interface [Microsoft TV Technologies],GetRecordVersionIndicator method, IISDB_SDTT.GetRecordVersionIndicator, IISDB_SDTT::GetRecordVersionIndicator, dvbsiparser/IISDB_SDTT::GetRecordVersionIndicator, mstv.iisdb_sdtt_getrecordversionindicator
f1_keywords:
- dvbsiparser/IISDB_SDTT.GetRecordVersionIndicator
dev_langs:
- c++
req.header: dvbsiparser.h
req.include-header: Dvbsiparser.idl
req.target-type: Windows
req.target-min-winverclnt: Windows 7 [desktop apps only]
req.target-min-winversvr: None supported
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: 
req.dll: 
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- dvbsiparser.h
api_name:
- IISDB_SDTT.GetRecordVersionIndicator
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IISDB_SDTT::GetRecordVersionIndicator


## -description


Receives the version indicator from a record
  in an Integrated Services Digital Broadcasting
  (ISDB)  software download
  trigger table
  (SDTT). 


## -parameters




### -param dwRecordIndex [in]

Specifies the record number, indexed from zero.
  Call the <a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nf-dvbsiparser-iisdb_sdtt-getcountofrecords">IISDB_SDTT::GetCountOfRecords</a> method to get the number of records in the SDTT.



### -param pbVal [out]

Receives the version indicator.



## -returns



If this method succeeds, it returns <b xmlns:loc="http://microsoft.com/wdcml/l10n">S_OK</b>. Otherwise, it returns an <b xmlns:loc="http://microsoft.com/wdcml/l10n">HRESULT</b> error code.




## -see-also




<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nn-dvbsiparser-iisdb_sdtt">IISDB_SDTT</a>



<a href="https://docs.microsoft.com/previous-versions/windows/desktop/api/dvbsiparser/nf-dvbsiparser-iisdb_sdtt-getcountofrecords">IISDB_SDTT::GetCountOfRecords</a>
 

 

