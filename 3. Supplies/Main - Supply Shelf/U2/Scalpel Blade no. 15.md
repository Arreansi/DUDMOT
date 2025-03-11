---
Alias:
  - None
Photo:
  - "![[Scalpel Blade no. 15.png]]"
Type:
  - Sterile Supply
Specialty:
  - Not Applicable
Category:
  - "[[Scalpel Blade]]"
Restock:
  - "[[U2#U2-5|U2-5]]"
Reference:
  - Not Applicable
Location:
  - Available in respective theatres and trolleys
Compatibility:
  - Not Applicable
Status:
  - Done
cssclasses:
  - 
---

>[!Item] `=this.file.name`
>![[Scalpel Blade no. 15.png]]
>>[!multi-column]
>>>[!Location]
>>>```dataview
>>>TABLE without id
>>>Location
>>>WHERE file.name = this.file.name
>>>SORT Status, file.name
>>
>>>[!Location] Restock Location
>>>```dataview
>>>TABLE without id
>>>Restock
>>>WHERE file.name = this.file.name
>>>SORT Status, file.name
>>
>>>[!example] Category
>>>```dataview
>>>TABLE without id
>>>Category
>>>WHERE file.name = this.file.name
>>>SORT Status, file.name
>>
>

---
## Reference %% fold %%
- https://m.media-amazon.com/images/W/MEDIAX_792452-T2/images/I/51CPX9dxUcL.jpg



