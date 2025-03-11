```dataview 
TABLE 
WITHOUT ID Instrument, 
Location
From Type = "Instrument"
```

```dataview 
TABLE WITHOUT ID Instrument
FLATTEN Location
WHERE Type = "Instrument"
```

```dataview
Table 
Location as "Loc."
FROM "2. Instruments"
SORT file.name
```


# Main Equipment

| Loc.                  | Main Equipment | Quantity | Notes |
| --------------------- |:-------------- |:--------:| ----- |
| ``[[My Note#^my-table]]`` | [[Sword]]      |    1     |       |
|                       | [[Shield]]     |    1     |       |

---

| Col 1                | Col 2              |
| -------------------- | ------------------ |
| `=this.file.inlinks` | `=this.file.ctime` | 



```
.someMetadataField
```
this.someMetadataField


Assignment due in `= this.due - date(today)`
Final paper due in `= [[Computer Science Theory]].due - date(today)`

🏃‍♂️ Goal reached? `= choice(this.steps > 10000, "YES!", "**No**, get moving!")`

You have `= length(filter(link(dateformat(date(today), "yyyy-MM-dd")).file.tasks, (t) => !t.completed))` tasks to do. `= choice(date(today).weekday > 5, "Take it easy!", "Time to get work done!")` 


