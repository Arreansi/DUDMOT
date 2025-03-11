---
Alias:
  - None
Photo:
  - "![[Basic Oral Tray.png]]"
Type:
  - Instrument Tray - Medium
Specialty:
  - Max-Fax
Category:
  - "[[Instrument Tray]]"
Restock:
  - Not Applicable
Reference:
  - Not Applicable
Storage:
  - Metal Instrument Crate
Location:
  - "[[M1#M1-4|M1-4]]"
Compatibility:
  - 
Status:
  - Done?
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
>>>![[Basic Oral Tray.png]]
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
| Quantity | Instrument                                  | Location                                                |
|:--------:|:------------------------------------------- |:------------------------------------------------------- |
|    2     | [[BP Handle no. 7]]                         | `=[[BP Handle no. 7]].location`                         |
|    1     | [[Adson Dissecting Forceps - Toothed]]      | `=[[Adson Dissecting Forceps - Toothed]].location`      |
|    1     | [[Waugh Dissecting Forceps]]                | `=[[Waugh Dissecting Forceps]].location`                |
|    1     | [[Waugh Dressing Forceps]]                  | `=[[Waugh Dressing Forceps]].location`                  |
|    1     | [[Gillies Dissecting Forceps]]              | `=[[Gillies Dissecting Forceps]].location`              |
|    1     | [[College Forceps]]                         | `=[[College Forceps]].location`                         |
|    1     | [[Howarth Elevator]]                        | `=[[Howarth Elevator]].location`                        |
|    1     | [[Periosteal Elevator]]                                  | `=[[Molt 9]].location`                                  |
|    1     | [[Miller Bone Curette - Straight]]          | `=[[Miller Bone Curette - Straight]].location`          |
|    1     | [[Mitchell Osteo-Trimmer]]                  | `=[[Mitchell Osteo-Trimmer]].location`                  |
|    1     | [[Suction American Pattern and Stillettte]] | `=[[Suction American Pattern and Stillettte]].location` |
|    1     | [[Suction Poole, no guard]]                 | `=[[Suction Poole, no guard]].location`                 |
|    1     | [[Minnesota Retractor]]                     | `=[[Minnesota Retractor]].location`                     |
|    1     | [[Tongue Depressor - Wide]]                 | `=[[Tongue Depressor - Wide]].location`                 |
|    1     | [[Tongue Depressor - Narrow]]               | `=[[Tongue Depressor - Narrow]].location`               |
|    1     | [[Cheek Retractor]]                         | `=[[Cheek Retractor]].location`                         |
>>>
>>>>[!Blank]
| Quantity | Instrument **_On Threader:_**         | Location                                          |
|:--------:|:------------------------------------- |:------------------------------------------------- |
|    1     | [[Mayo Needle Holder 5in]]           | `=[[Mayo Needle Holder 5 in]].location`           |
|    1     | [[Mayo Needle Holder 6in]]           | `=[[Mayo Needle Holder 6 in]].location`           |
|    1     | [[McIndoe Scissors]]                  | `=[[McIndoe Scissors]].location`                  |
|    1     | [[D.E. (Diamond Edge) Scissors 6in]] | `=[[D.E. (Diamond Edge) Scissors 6 in]].location` |
|    1     | [[SuperCut Tenotomy Scissors]]        | `=[[SuperCut Tenotomy Scissors]].location`        |
|    1     | [[Iris Scissors]]                     | `=[[Iris Scissors]].location`                     |
|    1     | [[Fickling Tissue Forceps - Toothed]] | `=[[Fickling Tissue Forceps - Toothed]].location` |
|    2     | [[Allis Tissue Forceps]]              | `=[[Allis Tissue Forceps]].location`              |
|    6     | [[Mosquito Artery Forceps - Curved]]  | `=[[Mosquito Artery Forceps - Curved]].location`  |
|    2     | [[Rampley Sponge Forceps]]            | `=[[Rampley Sponge Forceps]].location`            |
|    4     | [[Towel Clips - Blunt]]               | `=[[Towel Clips - Blunt]].location`               |
>>>>
>
>>[!info]- Individualized Instrument List
>>>[!multi-column]
>>>>[!Equip] Instruments
>>>>
|Quantity|Instrument|Location|
|:---:|:---:|:---:|
|**2**|[[BP Handle no. 7]]<br>![[BP Handle no. 7.png]]|`=[[BP Handle no. 7]].location`|
|**1**|[[Adson Dissecting Forceps - Toothed]]<br>![[Adson Dissecting Forceps - Toothed.png]]|`=[[Adson Dissecting Forceps - Toothed]].location`|
|**1**|[[Waugh Dissecting Forceps]]<br>![[Waugh Dissecting Forceps.png]]|`=[[Waugh Dissecting Forceps]].location`|
|**1**|[[Waugh Dressing Forceps]]<br>![[Waugh Dressing Forceps.png]]|`=[[Waugh Dressing Forceps]].location`|
|**1**|[[Gillies Dissecting Forceps]]<br>![[Gillies Dissecting Forceps.png]]|`=[[Gillies Dissecting Forceps]].location`|
|**1**|[[College Forceps]]<br>![[College Forceps.png]]|`=[[College Forceps]].location`|
|**1**|[[Howarth Elevator]]<br>![[Howarth Elevator.png]]|`=[[Howarth Elevator]].location`|
|**1**|[[Periosteal Elevator]]<br>![[Molt 9.png]]|`=[[Molt 9]].location`|
|**1**|[[Miller Bone Curette - Straight]]<br>![[Miller Bone Curette - Straight.png]]|`=[[Miller Bone Curette - Straight]].location`|
|**1**|[[Mitchell Osteo-Trimmer]]<br>![[Mitchell Osteo-Trimmer.png]]|`=[[Mitchell Osteo-Trimmer]].location`|
|**1**|[[Suction American Pattern and Stillettte]]<br>![[Suction American Pattern and Stillettte.png]]|`=[[Suction American Pattern and Stillettte]].location`|
|**1**|[[Suction Poole, no guard]]<br>![[Suction Poole, no guard.png]]|`=[[Suction Poole, no guard]].location`|
|**1**|[[Minnesota Retractor]]<br>![[Minnesota Retractor.png]]|`=[[Minnesota Retractor]].location`|
|**1**|[[Tongue Depressor - Wide]]<br>![[Tongue Depressor - Wide.png]]|`=[[Tongue Depressor - Wide]].location`|
|**1**|[[Tongue Depressor - Narrow]]<br>![[Tongue Depressor - Narrow.png]]|`=[[Tongue Depressor - Narrow]].location`|
|**1**|[[Cheek Retractor]]<br>![[Cheek Retractor.png]]|`=[[Cheek Retractor]].location`|
>>>
>>>>[!Example] Instruments **_On Threader:_**
>>>>
| Quantity |                                     Instrument                                      |                     Location                      |
|:--------:|:-----------------------------------------------------------------------------------:|:-------------------------------------------------:|
|  **1**   |                [[Mayo Needle Holder 5in]]<br>![[Mayo Needle Holder 5 in.png]]                |        `=[[Mayo Needle Holder 5 in]].location`         |
|  **1**   |                [[Mayo Needle Holder 6in]]<br>![[Mayo Needle Holder 6 in.png]]                |        `=[[Mayo Needle Holder 6 in]].location`         |
|  **1**   |                  [[McIndoe Scissors]]<br>![[McIndoe Scissors.png]]                  |         `=[[McIndoe Scissors]].location`          |
|  **1**   | [[D.E. (Diamond Edge) Scissors 6in]]<br>![[D.E. (Diamond Edge) Scissors 6 in.png]] | `=[[D.E. (Diamond Edge) Scissors 6 in]].location` |
|  **1**   |        [[SuperCut Tenotomy Scissors]]<br>![[SuperCut Tenotomy Scissors.png]]        |    `=[[SuperCut Tenotomy Scissors]].location`     |
|  **1**   |                     [[Iris Scissors]]<br>![[Iris Scissors.png]]                     |           `=[[Iris Scissors]].location`           |
|  **1**   | [[Fickling Tissue Forceps - Toothed]]<br>![[Fickling Tissue Forceps - Toothed.png]] | `=[[Fickling Tissue Forceps - Toothed]].location` |
|  **2**   |              [[Allis Tissue Forceps]]<br>![[Allis Tissue Forceps.png]]              |       `=[[Allis Tissue Forceps]].location`        |
|  **6**   |  [[Mosquito Artery Forceps - Curved]]<br>![[Mosquito Artery Forceps - Curved.png]]  | `=[[Mosquito Artery Forceps - Curved]].location`  |
|  **2**   |            [[Rampley Sponge Forceps]]<br>![[Rampley Sponge Forceps.png]]            |      `=[[Rampley Sponge Forceps]].location`       |
|  **4**   |               [[Towel Clips - Blunt]]<br>![[Towel Clips - Blunt.png]]               |        `=[[Towel Clips - Blunt]].location`        |
>>>>
>





