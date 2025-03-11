---
Type: Supply
Restock: Form#192
Reference: Stryker 5820-066-216
Photo:
  - "![[SD - Fissure Drill Bit 1.6mm.png]]"
Specialty:
  - Max-Fax
Location:
  - "[[Max-Fax Trolley#First Drawer]]"
Compatibility: "[[Signature Drill Set]]"
Status: To Check
cssclasses: 
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
>>>>[!machine] Compatibility
>>>>```dataview
>>>>TABLE without id
>>>>Compatibility
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
>>[!example]- Similar Drill List
>>![[Signature Drill Set#Signature Drill - Compatible Attachments]]
>
>>[!see]-  See Also
>>- ## [[Signature Drill Console]]  #mcl/list-card 
>>![[Signature Drill Console.png]] 
>>- ## [[E.Pen Drill - MaxFax]]  
>>![[E.Pen Drill - MaxFax.png]] 
>>- ## [[E.Pen Drill Console - MaxFax]]  
>>![[E.Pen Drill Console - MaxFax.png]] 
>>
