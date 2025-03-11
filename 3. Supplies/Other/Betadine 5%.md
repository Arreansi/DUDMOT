---
Alias:
  - 
Photo:
  - "![[Betadine 5%.png]]"
Type:
  - Liquids and Solutions
Specialty:
  - 
Category:
  - "[[Liquids and Solutions]]"
Restock:
  - 
Reference:
  - 
Location:
  - Fire Shelf?
Compatibility:
  - 
Status:
  - Need photo
cssclasses:
  - 
---

>[!Supply] `= this.file.name`
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