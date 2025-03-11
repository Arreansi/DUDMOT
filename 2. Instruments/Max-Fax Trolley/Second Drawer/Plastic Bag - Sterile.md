---
Alias:
  - 
Photo:
  - "![[Plastic Bag - Sterile.png]]"
Type:
  - Sterile Supply
Specialty:
  - Not Applicable
Category:
  - "[[Sterile Bag and Cover]]"
Restock:
  - To Add
Reference:
  - None
Location:
  - "[[Max-Fax Trolley#Second Drawer]]"
Compatibility:
  - Not Applicable
Status:
  - Done
cssclasses:
  - 
---

>[!General] `= this.file.name`
>>[!multi-column]
>>>[!Blank|wide-2]
>>>`= this.photo`
>>>
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
>>>
>>></br>
>>>
>>>>[!example] Category
>>>>```dataview
>>>>TABLE without id
>>>>Category
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name
>>
>

