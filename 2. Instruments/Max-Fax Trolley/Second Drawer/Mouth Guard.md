---
Alias:
- 
Photo:
  - "![[Mouth Guard.png]]"
Type: 
- Instrument
Specialty: 
- Max-Fax
Category: 
- "[[Max-Fax Supply]]"
Restock: 
- 
Reference:
- 
Location: 
- "[[Max-Fax Trolley#Second Drawer]]"
Compatibility:
- 
Status: 
- 
cssclasses:
- 
---

>[!MxFx] `= this.file.name`
>>[!multi-column]
>>>[!Blank|wide-2]
>>>`= this.photo`
>>
>>>[!Blank]
>>>>[!Location|]
>>>>```dataview
>>>>TABLE without id
>>>>Location
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name
>>>
>>></br>
>>>
>>>>[!example] Category
>>>>```dataview
>>>>TABLE without id
>>>>Category
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name 
>>>
>>></br>
>>>
>>>>[!Warning] Unsterile supply, only use on oral surgery.