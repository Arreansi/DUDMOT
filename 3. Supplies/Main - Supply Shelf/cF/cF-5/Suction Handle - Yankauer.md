---
Alias:
  - 
Photo:
  - "![[Suction Handle - Yankauer.png]]"
Type:
  - Sterile Supply
Specialty:
  - Max-Fax
Category:
  - "[[Suction Handle - Disposable]]"
Restock:
  - "[[CF#CF-5|CF-5]]"
Reference:
  - 
Location:
  - "[[CF#cF-5|CF-5]]"
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
>>>>[!example] Category
>>>>```dataview
>>>>TABLE without id
>>>>Category
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name
>
