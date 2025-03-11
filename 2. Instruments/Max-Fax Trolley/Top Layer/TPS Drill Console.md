---
Alias:
  - STRYKER CORE-1 Drill Console
Type:
  - Machine Equipment
Specialty:
  - Max-Fax
Category:
  - Machine
Restock:
  - None
Reference:
  - None
Location:
  - "[[Max-Fax Trolley#Top Layer]]"
Compatibility:
  - "[[TPS Oral Drill & Saw Tray]]"
Status:
  - WiP
cssclasses:
  - 
---

>[!MxFx] TPS Drill Console
>![[TPS Drill Console.png\|]]
>>[!multi-column]
>>>[!Location|]
>>>```dataview
>>>TABLE without id
>>>Location
>>>WHERE file.name = this.file.name
>>>SORT Status, file.name
>>
>>>[!Info] Alias
>>>```dataview
>>>TABLE without id
>>>Alias
>>>WHERE file.name = this.file.name
>>>SORT Status, file.name 
>
>>[!machine] Compatibility
>>```dataview
>>TABLE 
>>Location
>>WHERE contains(compatibility, "TPS Drill Console")
>>SORT Status, file.name 
>
>>[!Assembly]
>>TO ADD
>
>>[!example]- Equipment
>>![[TPS Oral Drill & Saw Tray#TPS Drill - Compatible Drill Bits]]
>
>>[!see]-  See Also
>>- ## [[Signature Drill Console]]  #mcl/list-card 
>>![[Signature Drill Console.png]] 
>>- ## [[E.Pen Drill Console - MaxFax]]  
>>![[E.Pen Drill Console - MaxFax.png]] 

