---
Alias:
  - 
Photo:
  - "![[Dental Syringe Needle.png]]"
Type:
  - Sterile Supply
Specialty:
  - Max-Fax
Category:
  - "[[Sterile Needle]]"
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
>>[!Assembly] Used with [[Dental Syringe]] and [[Dental Syringe Needle]]


---
## Reference %% fold %%
- https://www.nipro-group.com/sites/default/files/styles/twitte_share/public/2019-11/Dental%20needle%2027G%20-%20Vertical.png?itok=l7r_z4pw