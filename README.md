# bail-project

This repository currently contains a web scraper to collect the jail rosters for several counties in Mississippi. We are collecting this information on behalf of [The Bail Project](https://bailproject.org/).

This repository is an improved version of https://github.com/nsubbaian/BailProject.

Changes:
- Web Scraper
  - Rewrote web scraper from scratch
    - Web scrapers now include previously missing data
- Data Cleaner
  - Added a data cleaner to ensure data is consistent across counties
    - Renames columns that represent the same data
      - E.g. 'Arrest Agency' and 'Arresting Agency'
    - Renames data that represents the same category
      - E.g. Race - 'B', 'Black', and 'BLACK'
