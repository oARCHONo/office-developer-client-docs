---
title: "PidTagLastModificationTime Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidTagLastModificationTime
api_type:
- HeaderDef
ms.assetid: a64e5300-6865-4588-8e1b-158cfd9c60c2
description: "Contains the date and time when the object or subobject was last modified. This property is initially set to the same value as the PR_CREATION_TIME property. "
---

# PidTagLastModificationTime Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains the date and time when the object or subobject was last modified. 
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |PR_LAST_MODIFICATION_TIME  <br/> |
|Identifier:  <br/> |0x3008  <br/> |
|Data type:  <br/> |PT_SYSTIME  <br/> |
|Area:  <br/> |Message time  <br/> |
   
## Remarks

This property is initially set to the same value as the **PR_CREATION_TIME** ([PidTagCreationTime](pidtagcreationtime-canonical-property.md)) property. Attachment subobjects can update it as necessary by copying the last modification time maintained by the native file system. A client application can set this property until the first call to the [IMAPIProp::SaveChanges](imapiprop-savechanges.md) method. From then on the provider should update **PR_LAST_MODIFICATION_TIME** during every **IMAPIProp::SaveChanges** call. 
  
## Related resources

### Protocol specifications

[[MS-OXCMSG]](https://msdn.microsoft.com/library/7fd7ec40-deec-4c06-9493-1bc06b349682%28Office.15%29.aspx)
  
> Handles message and attachment objects.
    
[[MS-OXCFXICS]](https://msdn.microsoft.com/library/b9752f3d-d50d-44b8-9e6b-608a117c8532%28Office.15%29.aspx)
  
> Handles synchronizing messaging object data between a server and a client.
    
[[MS-OXOABK]](https://msdn.microsoft.com/library/f4cf9b4c-9232-4506-9e71-2270de217614%28Office.15%29.aspx)
  
> Specifies the properties and operations for lists of users, contacts, groups, and resources.
    
### Header files

Mapidefs.h
  
> Provides data type definitions.
    
Mapitags.h
  
> Contains definitions of properties listed as alternate names.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

