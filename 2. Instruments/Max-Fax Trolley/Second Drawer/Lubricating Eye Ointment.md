---
Alias:
  - "Poly Visc"
Photo:
  - "![[Lubricating Eye Ointment.png]]"
Type:
  - Supply
Specialty:
  - Max-Fax
Category:
  - "[[Cream & Ointments]]"
Restock:
  - Unknown
Reference:
  - None
Location:
  - "[[Max-Fax Trolley#Second Drawer]]"
Compatibility:
  - Not Applicable
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
>>>>[!info] Alias
>>>>```dataview
>>>>TABLE without id
>>>>Alias
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name
>>>
>>></br>
>>>
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
>
