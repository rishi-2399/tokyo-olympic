
<img align="left" alt="Coding" width="48%" src="https://github.com/rishi-2399/tokyo-olympic/blob/f1b3cfb9bdac243f609dd9ea58a44e3c9eaa489e/3.jpeg">
<img align="right" alt="Coding" width="48%" src="https://github.com/rishi-2399/tokyo-olympic/blob/f1b3cfb9bdac243f609dd9ea58a44e3c9eaa489e/4.jpeg">




<h3>Query Results</h3>
<img align="centre" alt="Coding" width="400" src="https://github.com/rishi-2399/tokyo-olympic/blob/22f7969202ea91e9c460a1af7db6545bd317c8f2/screenshots/athletes_pic.png">

* SELECT Country, COUNT(*) AS coaches_count FROM coaches GROUP BY Country;

<img align="centre" alt="Coding" width="400" src="https://github.com/rishi-2399/tokyo-olympic/blob/22f7969202ea91e9c460a1af7db6545bd317c8f2/screenshots/coaches_pic.png">

* SELECT Discipline, SUM(Male + Female) AS total_entries FROM entriesgender GROUP BY Discipline;

<img align="centre" alt="Coding" width="400" src="https://github.com/rishi-2399/tokyo-olympic/blob/22f7969202ea91e9c460a1af7db6545bd317c8f2/screenshots/entriesgender_pic.png">

* SELECT TeamCountry, SUM(Gold + Silver + Bronze) AS total_medals FROM medals GROUP BY TeamCountry;

<img align="centre" alt="Coding" width="400" src="https://github.com/rishi-2399/tokyo-olympic/blob/22f7969202ea91e9c460a1af7db6545bd317c8f2/screenshots/medals_pic.png">

* SELECT Country, Discipline, COUNT(*) AS teams_count FROM teams GROUP BY Country, Discipline ORDER BY teams_count DESC;

<img align="centre" alt="Coding" width="400" src="https://github.com/rishi-2399/tokyo-olympic/blob/22f7969202ea91e9c460a1af7db6545bd317c8f2/screenshots/teams_pic.png">
