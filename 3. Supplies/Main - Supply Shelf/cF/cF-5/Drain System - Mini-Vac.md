---
Alias:
  - 
Photo:
  - "![[Drain System - Mini-Vac.png]]"
Type:
  - Sterile Supply
Specialty:
  - Max-Fax
Category:
  - "[[Drain System]]"
Restock:
  - "[[CF#CF-5|CF-5]]"
Reference:
  - 
Location:
  - "[[CF#CF-5|CF-5]]"
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


---
## Reference %% fold %%
- https://www.capesmedical.co.nz/shop/Woundcare/Drainage/Medinorm+Mini+Bellows+Wound+drainage+system+40ml+CH6.html