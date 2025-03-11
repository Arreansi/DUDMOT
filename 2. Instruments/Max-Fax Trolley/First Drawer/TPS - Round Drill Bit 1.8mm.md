---
Alias:
  - 
Photo:
  - "![[TPS - Round Drill Bit 1.8mm.png]]"
Type:
  - SteriPeel
Specialty:
  - Max-Fax
Category:
  - 
Restock:
  - Conditional
Reference:
  - 
Location:
  - "[[Max-Fax Trolley#First Drawer]]"
Compatibility:
  - "[[TPS Oral Drill & Saw Tray]]"
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
>>>>[!machine] Compatibility
>>>>```dataview
>>>>TABLE without id
>>>>Compatibility
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name 
>>>
>>></br>
>>>
>>>>[!warning] Do not throw unless blade is dull. Order as necessary.
>
