---
Alias:
  - None
Photo:
  - "![[Medium Gauze Swab.png]]"
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

>[!Supply] `=this.file.name`
>![[Abdominal Gauze Swab.png]]
>
>>[!Warning] This X-Ray detectable swab sponge comes in 5 pieces per package
>
>>[!multi-column]
>>>[!Location]
>>>```dataview
>>>TABLE without id
>>>Location
>>>WHERE file.name = this.file.name
>>>SORT Status, file.name
>>
>>>[!example] Category
>>>```dataview
>>>TABLE without id
>>>Category
>>>WHERE file.name = this.file.name
>>>SORT Status, file.name
