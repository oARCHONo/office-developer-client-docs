---
title: "PidLidTaskDeadOccurrence Canonical Property"
 
 
manager: soliver
ms.date: 03/09/2015
ms.audience: Developer
ms.topic: reference
ms.prod: office-online-server
ms.localizationpriority: medium
api_name:
- PidLidTaskDeadOccurrence
api_type:
- COM
ms.assetid: e78287ff-f8cc-45ea-8da8-e7a7359e651c
description: "Indicates whether new occurrences must be generated. When a pattern's final instance is in the past or after a number of instances, it is no longer in effect."
---

# PidLidTaskDeadOccurrence Canonical Property

  
  
**Applies to**: Outlook 2013 | Outlook 2016 
  
Indicates whether new occurrences must be generated.
  
|Property |Value |
|:-----|:-----|
|Associated properties:  <br/> |dispidTaskDeadOccur  <br/> |
|Property set:  <br/> |PSETID_Task  <br/> |
|Long ID (LID):  <br/> |0x00008109  <br/> |
|Data type:  <br/> |PT_BOOLEAN  <br/> |
|Area:  <br/> |Task  <br/> |
   
## Remarks

A recurrence pattern is no longer in effect when its final instance is in the past or its specified number of instances has been generated. The client sets this property to FALSE for a new task or to TRUE when it generates the last instance of a recurring task. When you copy a task to generate a new instance, this property is set to TRUE on the copy, which is the completed instance.
  
## Related resources

### Protocol specifications

[[MS-OXPROPS]](https://msdn.microsoft.com/library/f6ab1613-aefe-447d-a49c-18217230b148%28Office.15%29.aspx)
  
> Provides property set definitions and references to related Exchange Server protocol specifications.
    
[[MS-OXOTASK]](https://msdn.microsoft.com/library/55600ec0-6195-4730-8436-59c7931ef27e%28Office.15%29.aspx)
  
> Defines several objects that model the electronic equivalent of tasks, task assignments, and task updates. 
    
### Header files

Mapidefs.h
  
> Provides data type definitions.
    
## See also



[MAPI Properties](mapi-properties.md)
  
[MAPI Canonical Properties](mapi-canonical-properties.md)
  
[Mapping Canonical Property Names to MAPI Names](mapping-canonical-property-names-to-mapi-names.md)
  
[Mapping MAPI Names to Canonical Property Names](mapping-mapi-names-to-canonical-property-names.md)

