# dataset_ufo

## About

We used nuforc.org to scrape all of the sighting details for ufo sightings reported.

The webpage is still up and running making it still available for scraping. 

## Data dictionary

| Header                         | Description                                                                                                                                                                                                                                                                                                                                  |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| details                           | Url for the sighting on the website.                                 |
| date                    | Date in which the UFO spotting occurred.                                        |
| city                           | City in which the UFO spotting occurred.                                                       |
| state                    | State in which the UFO spotting occurred.                                                                        |
| country                        | Country in which the UFO spotting occurred.                                                                             |
| shape                          | Reported shape of the UFO sighting.                                                                   |
| summary                         | Summary of what occurred during the UFO sighting.                                                   |
| report date                      | Date in which the UFO sighting was reported. |
| posted date                        |  Date in which the UFO sighting was posted on NUFORC.                                                  

## To do list

- [x] Scape data from nuforc into seperate CSVs
- [x] Cleaned scraped data to increase usability
- [x] Merge all CSVs into one single dataset
- [ ] Clean integrated data


## Changelog
- Scraped data from nuforc.org
- Successfully extracted, cleaned, and structured the collected data.
- Integrated the cleaned data from different scraping files into one merged table using R.
- Ensured data consistency and accuracy through the cleaning and integration process.

## Notes 
The National UFO Reporting Center (NUFORC) is a widely recognized and reputable organization that collects and documents reports of UFO (Unidentified Flying Object) sightings. NUFORC provides a platform for individuals to submit their accounts of UFO sightings and experiences.NUFORC's primary mission is to gather and disseminate information about UFO sightings to promote open dialogue and research in this field.