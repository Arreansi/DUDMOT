---
Alias:
  - 
Photo:
  - "![[Toothbrush - Sterile.png]]"
Type:
  - Sterile Supply
Specialty:
  - Max-Fax
Category:
  - Unknown
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
>>>[!Blank]
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
>>>>[!machine] Category
>>>>```dataview
>>>>TABLE without id
>>>>Category
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name 
>