# Thai GL Watch History

```dataview
TABLE Status, Rating, Date_Started AS "Date Started", Date_Finished AS "Finished On"
FROM "02 - Media Tracker/TV Shows/Thai GLs"
WHERE Type = "Thai GL"
SORT Date_Started
 desc
```