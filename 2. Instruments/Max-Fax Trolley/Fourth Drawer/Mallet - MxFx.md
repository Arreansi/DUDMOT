---
Alias:
  - 
Photo:
  - "![[Mallet.png]]"
Type:
  - Instrument
Specialty:
  - Orthopaedic
Category:
  - "[[Mallets]]"
Restock:
  - 
Reference:
  - AESCULAP DX545R
Location:
  - "[[Max-Fax Trolley#Fourth Drawer]]"
SubLocation:
  - "[[Maxillo-Facial Osteotomy Tray - New]]"
  - "[[Maxillo-Facial Osteotomy Tray - Old]]"
  - "[[Third Molar Set]]"
Compatibility:
  - 
Status:
  - 
cssclasses:
  - 
---

>[!Ortho] `=this.file.name`
>>[!multi-column]
>>>[!Blank|wide-3]
>>>![[Mallet.png]]
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
>>>>[!See] Other Location
>>>>```dataview
>>>>TABLE without id
>>>>SubLocation as "Other Location"
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
