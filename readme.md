A GitHub Action fetches [the complete record of the FSA's open food hygiene rating data](https://ratings.food.gov.uk/open-data#:~:text=Downloadable%20open%20data%20file) daily and commits it to this repo.

If there's no change in the file, there'll be no commit for that day. The commit name is (usually) of the format `Fetch FHRS_All_en-GB.csv for $(date)`.
