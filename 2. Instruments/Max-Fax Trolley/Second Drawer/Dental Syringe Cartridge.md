---
Alias:
  - XYLESTESIN™ - A 1.7 mL
Photo:
  - "![[Dental Syringe Cartridge.png]]"
Type:
  - Sterile Supply
Specialty:
  - Max-Fax
Category:
  - "[[Local Anesthetic Solution]]"
Restock:
  - "[[CJ#cJ-3|cJ-3]]"
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

>[!MxFx] `= this.file.name`
>>[!multi-column]
>>>[!Blank|wide-2]
>>>`= this.photo`
>>>
>>>>[!Info] A mixture of 2% Lidocaine and Epinephrine (Adrenaline) 1/80,000 
>>>
>>>>[!Assembly] Used with [[Dental Syringe]] and [[Dental Syringe Needle]]
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
>
