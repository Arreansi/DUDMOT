---
Alias:
  - None
Photo:
  - "![[Abdominal Gauze Swab.png]]"
Type:
  - Sterile Supply
Specialty:
  - Max-Fax
Category:
  - "[[Gauze Swabs]]"
Restock:
  - Not Applicable
Reference:
  - None
Location:
  - "[[CG#CG-3|CG-3]]"
Compatibility:
  - Not Applicable
Status:
  - Done
cssclasses:
  - 
---

>[!Item] `= this.file.name`
>>[!multi-column]
>>>[!Blank|wide-3]
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
>>>
>>></br>
>>>
>>>>[!Warning] This X-Ray detectable swab sponge comes in 5 pieces per package.
>>>