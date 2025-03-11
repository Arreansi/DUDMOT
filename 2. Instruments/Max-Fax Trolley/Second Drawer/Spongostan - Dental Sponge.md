---
Alias:
  - 
Photo:
  - "![[Spongostan - Dental Sponge.png]]"
Type:
  - Sterile Supply
Specialty:
  - Max-Fax
Category:
  - "[[Absorbable Haemostatic Gelatin Sponge]]"
Restock:
  - Form#192
Reference:
  - "Ethicon - MS0005"
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
>>>
>>></br>
>>>
>>>>[!warning] Restock with Form 192
>>>>```dataview
>>>>TABLE without id
>>>>Reference
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name 
>