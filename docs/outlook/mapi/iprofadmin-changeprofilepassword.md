---
title: "IProfAdminChangeProfilePassword"
 
 
manager: soliver
ms.date: 11/16/2014
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- IProfAdmin.ChangeProfilePassword
api_type:
- COM
ms.assetid: a41f707a-5c84-49aa-aeb6-469b2600e181
---

# IProfAdmin::ChangeProfilePassword

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Deprecated. Changes the password for a profile.
  
```cpp
HRESULT ChangeProfilePassword(
  LPSTR lpszProfileName,
  LPSTR lpszOldPassword,
  LPSTR lpszNewPassword,
  ULONG ulFlags
);
```

## Parameters

 _lpszProfileName_
  
> [in] A pointer to the name of the profile associated with the password to be changed.
    
 _lpszOldPassword_
  
> [in] A pointer to the current password.
    
 _lpszNewPassword_
  
> [in] A pointer to the new password.
    
 _ulFlags_
  
> [in] A bitmask of flags that controls the type of the passed-in strings. The following flag can be set:
    
MAPI_UNICODE 
  
> The profile name and passwords are in Unicode format. If the MAPI_UNICODE flag is not set, these strings are in ANSI format.
    
## Return value

S_OK 
  
> If this method is called, it will return S_OK. However, no action will be taken.
    
## Remarks

Do not use this method. MAPI does not support passwords for profiles.
  
## See also



[IProfAdmin : IUnknown](iprofadminiunknown.md)

