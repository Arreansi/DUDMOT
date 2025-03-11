---
share: "true"
---

# Equipment
---

## Machine Equipment

>[!Setting] Machine Equipment
>```dataview
>TABLE
>Alias, Location, Compatibility, Photo
>WHERE econtains(Type, "Machine Equipment")
>SORT file.name
>```







## Positioning Equipment

>[!Pos] Positioning Equipment
>```dataview
>TABLE
>Alias, Location, Photo
>WHERE econtains(Type, "Positioning Equipment")
>SORT file.name
>```

## Machine List
>[!Equip] Machine List
>>[!warning] List outdated. The original Excel file was created back on 2023-12-11
>
>>[!warning] Power Cable might be inaccurate. Difficult to track since its interchangeable between machines
>
>>[!warning] Machine location might change due to day-to-day event
>
>>[!Multi-Column]
>>> [!General] Surgical Machine List
>>>```dataview
>>>LIST
>>>WHERE econtains(Type, "Machine List") and econtains(Specialty, "Surgical")
>>>SORT file.name
>>>```
>>
>>>[!Blank]
>>>>[!Cardio] Cardiac-Related Machine List
>>>>```dataview
>>>>LIST
>>>>WHERE econtains(Type, "Machine List") and econtains(Specialty, "Cardiac")
>>>>SORT file.name
>>>>```
>>>
>>><br>
>>>
>>>>[!Supply] Anaesthetic Machine List
>>>>```dataview
>>>>LIST
>>>>WHERE econtains(Type, "Machine List") and econtains(Specialty, "Anaesthetic")
>>>>SORT file.name
>>>>```
>>>
>>><br>
>>>
>>>>[!Equip] Misc. Machine List
>>>>```dataview
>>>>LIST
>>>>WHERE econtains(Type, "Machine List") and econtains(Specialty, "All")
>>>>SORT file.name
>>>>```
>>>
>>><br>
>>>
>>>>[!Pos] Paediatrician Machine List
>>>>```dataview
>>>>LIST
>>>>WHERE econtains(Type, "Machine List") and econtains(Specialty, "Paediatrician")
>>>>SORT file.name
>>>>```
>>>
>>><br>
>>>
>>>>[!Equip] Other
>>>>```dataview
>>>>LIST
>>>>WHERE econtains(Type, "Machine List") and econtains(Specialty, "Other")
>>>>SORT file.name
>>>>```