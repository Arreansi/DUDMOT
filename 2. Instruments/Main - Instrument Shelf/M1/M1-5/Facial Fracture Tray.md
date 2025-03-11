---
Alias:
  - None
Photo:
  - "![[Facial Fracture Set.png]]"
Type:
  - Not Applicable
Specialty:
  - Max-Fax
Category:
  - "[[To add]]"
Restock:
  - Not Applicable
Reference:
  - Not Applicable
Storage:
  - Metal Instrument Crate
Location:
  - "[[M1#M1-5|M1-5]]"
Compatibility:
  - 
Status:
  - Category?
cssclasses:
  - 
---

>[!MxFx] `=this.file.name`
>>[!multi-column]
>>>[!Blank|wide-3]
>>>![[Facial Fracture Set.png]]
>>
>>>[!Blank]
>>>>[!Location]
>>>>```dataview
>>>>TABLE without id
>>>>Location
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name
>>>
>>></br>
>>>
>>>>[!Machine] Stored in
>>>>```dataview
>>>>TABLE without id
>>>>Storage
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name
>
>>[!example]+ Instrument List
>>>[!multi-column]
>>>>[!Blank]
>>>>
| Quantity | Instrument                                    |
|:-------: |:--------------------------------------------- |
| 1    | [[Curved Awls - Small]]                       |
| 1    | [[Curved Awls - Medium]]                      |
| 2    | [[Probes - Round]]                            |
| 1    | [[Ligature Hook]]                             |
| 1    | [[Steinhauser Bone Clamp - Angled]]           |
| 2    | [[Phrenic Nerve Retractor]]              |
| 1   | [[Wire Cutter - Angled]]           |
| 1    | [[Bending Pliers]]                            |
| 1    | [[Band Pusher]]                               |
| 1   | [[Corwin Wire Twister]]                       |
>>>
>>>>[!Blank]
| Quantity | Instruments **_On Threader:_**                        |
|:--------:| --------------------------------------------- |
|    8     | [[Spencer-Wells Artery Forceps - Short]]      |
|    4     | [[Spencer-Wells Artery Forceps - Round Body]] |
|    4     | [[Artery Forceps - Round End]]                |
|    4     | Needle Holder                                              |
>>>>
>
>>[!info]- Individualized Instrument List
>>>[!multi-column]
>>>>[!Equip] Instruments
>>>>
| Quantity | Instrument                                                                           | Location                                        |
| :------: | ------------------------------------------------------------------------------------ | ----------------------------------------------- |
| 1        | [[Curved Awls - Small]]<br>![[Curved Awls - Small.png]]                         | `=[[Curved Awls - Small]].location`             |
| 1        | [[Curved Awls - Medium]]<br>![[Curved Awls - Medium.png]]                       | `=[[Curved Awls - Medium]].location`            |
| 2        | [[Probes - Round]]<br>![[Probes - Round.png]]                                   | `=[[Probes - Round]].location`                  |
| 1        | [[Ligature Hook]]<br>![[Ligature Hook.png]]                                     | `=[[Ligature Hook]].location`                   |
| 1        | [[Steinhauser Bone Clamp - Angled]]<br>![[Steinhauser Bone Clamp - Angled.png]] | `=[[Steinhauser Bone Clamp - Angled]].location` |
| 2        | [[Phrenic Nerve Retractor]]<br>![[Phrenic Nerve Retractor.png]]                 | `=[[Phrenic Nerve Retractor]].location`         |
| 1        | [[Wire Cutter - Angled]]<br>![[Wire Cutter - Angled.png]]                       | `=[[Wire Cutter - Angled]].location`            |
| 1        | [[Bending Pliers]]<br>![[Bending Pliers.png]]                                   | `=[[Bending Pliers]].location`                  |
| 1        | [[Band Pusher]]<br>![[Band Pusher.png]]                                         | `=[[Band Pusher]].location`                     |
| 1        | [[Corwin Wire Twister]]<br>![[Corwin Wire Twister.png]]                         | `=[[Corwin Wire Twister]].location`             |
>>>
>>>>[!Example] Instruments **_On Threader:_**
>>>>
| Quantity | Instruments **_On Threader:_**                                                                      | Location                                                  |
|:--------:| --------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
|    8     | [[Spencer-Wells Artery Forceps - Short]]<br>![[Spencer-Wells Artery Forceps - Short.png]]           | `=[[Spencer-Wells Artery Forceps - Short]].location`      |
|    4     | [[Spencer-Wells Artery Forceps - Round Body]]<br>![[Spencer-Wells Artery Forceps - Round Body.png]] | `=[[Spencer-Wells Artery Forceps - Round Body]].location` |
|    4     | [[Artery Forceps - Round End]]<br>![[Artery Forceps - Round End.png]]                               | `=[[Artery Forceps - Round End]].location`                |
|    4     | [[Needle Holder]]<br>![[Needle Holder.png]]                                                         | `=[[Needle Holder]].location`                             |
>>>>
>
