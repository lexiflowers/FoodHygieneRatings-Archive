A GitHub Action fetches [the complete record of the FSA's open food hygiene rating data](https://ratings.food.gov.uk/open-data#:~:text=Downloadable%20open%20data%20file) daily and commits it to this repo.

The commit name is (usually) of the format `Fetch FHRS_All_en-GB.csv for $(date)`, unless there's no change in the source data, in which case, the commit will be empty and the message will be of format `No changes for $(date)`.
