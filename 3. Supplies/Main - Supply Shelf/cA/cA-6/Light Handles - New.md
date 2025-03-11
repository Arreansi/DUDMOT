---
Alias:
  - None
Photo:
  - "![[Light Handles - New.png]]"
Type:
  - Sterile Supply
Specialty:
  - Max-Fax
Category:
  - "[[Light Handles]]"
Restock:
  - Not Applicable
Reference:
  - None
Location:
  - "[[CA#CA-6|CA-6]]"
Compatibility:
  - Not Applicable
Status:
  - Done
cssclasses:
  - 
---

>[!Item] `= this.file.name`
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

---
## Reference %% fold %%
- https://www.draeger.com/Content/Documents/Products/disposable-handle-polaris-pi-9107166-en-master.pdf