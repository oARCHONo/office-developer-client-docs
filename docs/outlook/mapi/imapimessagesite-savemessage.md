---
title: "IMAPIMessageSiteSaveMessage"
description: "Describes the syntax, parameters, and return value of IMAPIMessageSiteSaveMessage, which requests that the current message be saved."
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- IMAPIMessageSite.SaveMessage
api_type:
- COM
ms.assetid: 94c44952-d297-4705-9778-90373dfa5ad6
---

# IMAPIMessageSite::SaveMessage

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Requests that the current message be saved.
  
```cpp
HRESULT SaveMessage( void );
```

## Parameters

None.
  
## Return value

S_OK 
  
> The call succeeded and has returned the expected value or values. 
    
## Remarks

Forms call the **IMAPIMessageSite::SaveMessage** method to request that a message be saved. 
  
For a list of interfaces related to form servers, see [MAPI Form Interfaces](mapi-form-interfaces.md).
  
## MFCMAPI reference

For MFCMAPI sample code, see the following table.
  
|**File**|**Function**|**Comment**|
|:-----|:-----|:-----|
|MyMAPIFormViewer.cpp  <br/> |CMyMAPIFormViewer::SaveMessage  <br/> |MFCMAPI uses the **IMAPIMessageSite::SaveMessage** method to save the message. |
   
## See also



[IMAPIMessageSite : IUnknown](imapimessagesiteiunknown.md)


[MFCMAPI as a Code Sample](mfcmapi-as-a-code-sample.md)
  
[MAPI Form Interfaces](mapi-form-interfaces.md)

