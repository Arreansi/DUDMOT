---
Alias:
  - None
Photo:
  - "![[Extraction Forceps Tray.png]]"
Type:
  - Not Applicable
Specialty:
  - Max-Fax
Category:
  - "[[Instrument Tray, Max-Fax]]"
Restock:
  - Not Applicable
Reference:
  - Not Applicable
Storage:
  - Metal Instrument Crate - Medium
Location:
  - "[[M1#M1-5|M1-5]]"
Compatibility:
  - 
Status:
  - 
cssclasses:
  - 
---

>[!MxFx] `=this.file.name`
>>[!multi-column]
>>>[!Blank|wide-3]
>>>![[Extraction Forceps Tray.png]]
>>
>>>[!Blank]
>>>>[!example]+ Instrument List
>>>>
| Number | Dental Extraction Forcep |
|:------:|:------------------------:|
|   1    |            29            |
|   2    |      94 Right Side       |
|   3    |            2             |
|   4    |           107            |
|   5    |           76N            |
|   6    |           163            |
|   7    |            76            |
|   8    |        159 / FX7         |
|   9    |       95 Left Side       |
|   10   |           137            |
|   11   |           74N            |
|   12   |           DK61           |
|   13   |            73            |
>>>>
>
>>[!multi-column]
>>>[!Location]
>>>```dataview
>>>TABLE without id
>>>Location
>>>WHERE file.name = this.file.name
>>>SORT Status, file.name
>>
>>>[!Machine] Stored in
>>>```dataview
>>>TABLE without id
>>>Storage
>>>WHERE file.name = this.file.name
>>>SORT Status, file.name
