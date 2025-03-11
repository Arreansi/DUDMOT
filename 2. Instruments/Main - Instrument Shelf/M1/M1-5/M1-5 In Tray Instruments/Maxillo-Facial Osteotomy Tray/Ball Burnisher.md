---
Alias:
  - 
Photo:
  - "![[Ball Burnisher.png]]"
Type:
  - Instrument
Specialty:
  - Max-Fax
Category:
  - "[[Max-Fax Instrument]]"
Restock:
  - 
Reference:
  - 3C1825
Location:
  - "[[Maxillo-Facial Osteotomy Tray - New]]"
  - "[[Maxillo-Facial Osteotomy Tray - Old]]"
Compatibility:
  - 
Status:
  - 
cssclasses:
  - 
---
>[!Blank]
>>[!Multi-Column]
>>>[!Home] [[Home]]
>>
>>>[!lib1] [[Surgery List]]
>>
>>>[!Item] [[Instruments]]
>>
>>>[!Supply] [[Supplies]]
>>
>>>[!Equip] [[Equipment]]
>



>[!MxFx] `=this.file.name`
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
>>>>[!example] Category
>>>>```dataview
>>>>TABLE without id
>>>>Category
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name
