---
title: "PidLidBusinessCardDisplayDefinition Canonical Property"
description: Outlines the PidLidBusinessCardDisplayDefinition canonical property, which contains user-customization details for displaying a contact as a business card.
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidLidBusinessCardDisplayDefinition
api_type:
- COM
ms.assetid: c0b956dd-7139-49e3-a32a-d70bfb11e0b1
---

# PidLidBusinessCardDisplayDefinition Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Contains user-customization details for displaying a contact as a business card.
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |dispidBCDisplayDefinition  <br/> |
|Property set:  <br/> |PSETID_Address  <br/> |
|Long ID (LID):  <br/> |0x00008040  <br/> |
|Data type:  <br/> |PT_BINARY  <br/> |
|Area:  <br/> |Contact  <br/> |
   
## Remarks

The layout of a business card can be represented as an image and a number of text fields. The image can be either a contact photo, or a card picture. Text fields consist of a value from another property set on the contact and an optional customized label string provided by the user. Note that multi-byte values are stored in little-endian format in the buffer.
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides property set definitions and references to related Exchange Server protocol specifications.
    
[[MS-OXOCNTC]](https://msdn.microsoft.com/library/9b636532-9150-4836-9635-9c9b756c9ccf%28Office.15%29.aspx)
  
> Specifies the properties and operations that are permissible for contacts and personal distribution lists.
    
### Header files

Mapidefs.h
  
> Provides data type definitions.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

