---
Alias:
  - 
Photo:
  - "![[Marking Pen.png]]"
Type:
  - Sterile Supply
Specialty:
  - Max-Fax
Category:
  - To add
Restock:
  - "[[CF#CF-3|CF-3]]"
Reference:
  - 
Location:
  - "[[CF#CF-3|CF-3]]"
Compatibility:
  - 
Status:
  - 
cssclasses:
  - 
---

>[!supply] `= this.file.name`
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
>>>>[!Location] Restock Location
>>>>```dataview
>>>>TABLE without id
>>>>Restock
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name
>