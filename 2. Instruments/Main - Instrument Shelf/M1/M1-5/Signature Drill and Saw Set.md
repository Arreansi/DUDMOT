---
Alias:
  - None
Photo:
  - "![[Signature Saw Set.png]]"
Type:
  - "Instrument Tray - Medium"
Specialty:
  - Max-Fax
Category:
  - "[[Instrument Tray, Max-Fax]]"
Restock:
  - Not Applicable
Reference:
  - Not Applicable
Similar:
  - "[[Signature Drill Set]]"
Location:
  - "[[M1#M1-5|M1-5]]"
Compatibility:
  - "[[Signature Drill Console]]"
Status:
  - Change Design?
cssclasses:
  - 
---

>[!MxFx] `=this.file.name`
>>[!multi-column]
>>>[!Blank|wide-2]
>>>![[Signature Saw Set.png]]
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
>>>>[!Machine] Compatibility
>>>>```dataview
>>>>TABLE without id
>>>>Compatibility
>>>>WHERE file.name = this.file.name
>>>>SORT Status, file.name
>>>
>>></br>
>>>
>>>>[!Example] Similar to
>>>>```dataview
>>>>TABLE without id
>>>>file.link as "Instrument Tray"
>>>>WHERE file.name = "Signature Drill Set"
>>>>SORT Status, file.name
>>>
>
>>[!Equip] Signature Saw Set - Instruments
>>>[!multi-column]
>>>>[!Blank]
>>>>![[Signature Saw Set A.png]]
>>>
>>>>[!Blank]
| #   | Signature Saw Set | Product Number         | Quantity |
| :---: | ----------------- | ---------------------- |:--------: |
| A   | 5100-004-000      | RemB Cord              | 1        |
| B   | 6400-031-000      | RemB Oscillating Saw   | 1        |
| C   | 6400-034-000      | RemB Sagittal Saw      | 1        |
| D   | 6400-037-000      | RemB Reciprocating Saw | 1        |
>>>>
>

---
## Signature Saw Set Attachment Assembly Guide

>[!Assembly]- Signature Saw Assembly
>>[!multi-column]
>>>[!Info] RemB Cord to Machine
>>>>![[RemB Cord A.png|500]]
>>>>Align Red Circular Orientation Mark with the appropriate port before installing.
>>
>>>[!Info] RemB Cord to Attachment
>>>>![[RemB Cord B.png|500]]
>>>>Align White Triangular Orientation Mark with the appropriate attachment before installing.

>[!Assembly]- RemB Oscillating Saw Blade Assembly
>>[!Info] **Instructions as stated in the manual.**
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Oscillating Saw A.png]]
>>>
>>>>[!Blank|wide-3]
>>>>1. Insert the blade into the gap in the blade mount
>>
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Oscillating Saw B.png]]
>>>
>>>>[!Blank|wide-3]
>>>>2. Fully push the collar up and seat the blade against the post, then release the collar.
>>
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Oscillating Saw C.png]]
>>>
>>>>[!Blank|wide-3]
>>>>3. Rotate the blade against the post until it snaps into the desired location. If necessary, push the collar up again to reposition the blade.
>>>>4. Gently tug the blade to verify the blade is secure.
>>
>>**Removal:**
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Oscillating Saw D.png]]
>>>
>>>>[!Blank|wide-3]
>>>>1. Fully push the collar up.
>>>>2. Remove the blade from the handpiece.

>[!Assembly]- RemB Sagittal Saw Blade Assembly
>>[!Info] **Instructions as stated in the manual.**
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Sagittal Saw A.png]]
>>>
>>>>[!Blank|wide-3]
>>>>1. Insert the blade into the gap in the blade mount.
>>
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Sagittal Saw B.png]]
>>>
>>>>[!Blank|wide-3]
>>>>2. Fully depress the button and seat the blade against the post. 
>>>>3. Release the button.
>>
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Sagittal Saw C.png]]
>>>
>>>>[!Blank|wide-3]
>>>>4. Fully depress the button and seat the blade against the post. Release the button.
>>
>>>[!Blank]
>>>5. Gently tug the blade to verify the blade is secure.
>>>6. To index the blade mount, pull out and rotate the blade mount until it snaps into the desired location.
>>
>>>[!Blank]
>>>**Note:** The blade mount will index in 45-degree increments, or  eight possible locations.
>>>![[RemB Sagittal Saw D.png|720]]
>>
>>**Removal:**
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Sagittal Saw E.png|720]]
>>>
>>>>[!Blank|wide-3]
>>>>1. Fully depress the button.
>>>>2. Remove the blade from the handpiece.

>[!Assembly]- RemB Reciprocating Saw Blade Assembly
>>[!Info] **Instructions as stated in the manual.**
>>>- The blade will install in two positions that are 180 degrees apart.
>>>- Two cutting accessory alignment marks are located at the distal end of the handpiece to facilitate the alignment of the blade during installation.
>>>- Some blades have a safety line on the shaft that will disappear inside the handpiece when the blade is properly installed.
>>
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Reciprocating Saw A.png]]
>>>
>>>>[!Blank|wide-3]
>>>>1. Fully depress the button.
>>>>2. Align the blade teeth with one of the cutting accessory alignment marks and fully insert the blade into the blade receptacle.
>>
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Reciprocating Saw B.png]]
>>>
>>>>[!Blank|wide-3]
>>>>3. Release the button. Slightly rotate the blade until the button snaps into position and engages the blade.
>>>>4. Gently tug the blade to verify the blade is secure.
>>
>>**Removal:**
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[RemB Reciprocating Saw C.png]]
>>>
>>>>[!Blank|wide-3]
>>>>1. Unplug the cord from the console and from the handpiece.
>>>>2. Remove cutting accessory as described above.


---
## Signature Saw Set Compatible Accessory List

>[!example]- Signature Saw Set | Oscillating and Sagittal Saw - Compatible Accessory
>
><br>
>
>>[!Accessory]
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[SD - Precision Thin Oscillating Blade.png]] 
>>>
>>>>[!Blank|wide-3]
>>>>>[!MxFx]
>>>>>```dataview
>>>>>TABLE without id
>>>>>file.link as "Compatible Accessory"
>>>>>WHERE file.name = "SD - Precision Thin Oscillating Blade"
>>>>>SORT Status, file.name
>>>>
>>>>>[!example] Reference
>>>>>```dataview
>>>>>TABLE without id
>>>>>Reference
>>>>>WHERE file.name = "SD - Precision Thin Oscillating Blade"
>>>>>SORT Status, file.name 
>
>>[!Accessory]
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[SD - Precision Thin Offset Oscillating Blade.png]] 
>>>
>>>>[!Blank|wide-3]
>>>>>[!MxFx]
>>>>>```dataview
>>>>>TABLE without id
>>>>>file.link as "Compatible Accessory"
>>>>>WHERE file.name = "SD - Precision Thin Offset Oscillating Blade"
>>>>>SORT Status, file.name
>>>>
>>>>>[!example] Reference
>>>>>```dataview
>>>>>TABLE without id
>>>>>Reference
>>>>>WHERE file.name = "SD - Precision Thin Offset Oscillating Blade"
>>>>>SORT Status, file.name 

>[!example]- Signature Saw Set | Reciprocating Saw- Compatible Accessory
>
><br>
>
>>[!Accessory]
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[SD - Precision Thin Saw Blade.png]] 
>>>
>>>>[!Blank|wide-3]
>>>>>[!MxFx]
>>>>>```dataview
>>>>>TABLE without id
>>>>>file.link as "Compatible Accessory"
>>>>>WHERE file.name = "SD - Precision Thin Saw Blade"
>>>>>SORT Status, file.name
>>>>
>>>>>[!example] Reference
>>>>>```dataview
>>>>>TABLE without id
>>>>>Reference
>>>>>WHERE file.name = "SD - Precision Thin Saw Blade"
>>>>>SORT Status, file.name 
>>>
>
>>[!Accessory]
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[SD - Precision Thin Saw Blade Extended Shank.png]] 
>>>
>>>>[!Blank|wide-3]
>>>>>[!MxFx]
>>>>>```dataview
>>>>>TABLE without id
>>>>>file.link as "Compatible Accessory"
>>>>>WHERE file.name = "SD - Precision Thin Saw Blade Extended Shank"
>>>>>SORT Status, file.name
>>>>
>>>>>[!example] Reference
>>>>>```dataview
>>>>>TABLE without id
>>>>>Reference
>>>>>WHERE file.name = "SD - Precision Thin Saw Blade Extended Shank"
>>>>>SORT Status, file.name 
>>>
>
>>[!Accessory]
>>>[!multi-column] 
>>>>[!Blank]
>>>>![[SD - Precision Thin Saw Blade Curved Banana.png]] 
>>>
>>>>[!Blank|wide-3]
>>>>>[!MxFx]
>>>>>```dataview
>>>>>TABLE without id
>>>>>file.link as "Compatible Accessory"
>>>>>WHERE file.name = "SD - Precision Thin Saw Blade Curved Banana"
>>>>>SORT Status, file.name
>>>>
>>>>>[!example] Reference
>>>>>```dataview
>>>>>TABLE without id
>>>>>Reference
>>>>>WHERE file.name = "SD - Precision Thin Saw Blade Curved Banana"
>>>>>SORT Status, file.name 
>>

---

## Reference %% fold %%
- https://www.stryker.com/content/dam/stryker/about/our-locations/apac/ifus/10-11-21/instruments/5100-004-700_Rev%20D.pdf
- https://shorturl.at/KfaeJ
- https://labeling.stryker.com/hcp/XHR/US/pthxr?keycode=07613154938308
- https://www.stryker.com/content/dam/stryker/about/our-locations/apac/ifus/10-11-21/instruments/6400-034-700_Rev%20AA.pdf
- https://shorturl.at/vgLbK
- https://labeling.stryker.com/hcp/XHR/US/pthxr?keycode=07613154938339