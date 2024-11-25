`= link("interstitialJournal/" + dateformat( date(today), "y/y-MM-dd"), "Create or go to Daily Note")`

Stream Projects
[[Learning Nix]]
[[Desired Nix Goals]]



```dataview 
TABLE dateformat(file.mtime, "dd.MM.yyyy - HH:mm") AS "Last modified" FROM "" SORT file.mtime DESC LIMIT 25 
```
