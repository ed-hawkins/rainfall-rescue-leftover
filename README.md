# rainfall-rescue-leftover
This repository records basic information about the 'leftover' monthly rainfall sheets from the [Rainfall Rescue project](https://github.com/ed-hawkins/rainfall-rescue). 

The rainfall sheets for all the long duration rainfall sites and most of the shorter duration sites were processed in detail by the project, to produce records in the main project GitHub repositories. The remaining 'leftover' sheets 
(about 7200 of them) did not undergo the same level of processing. They have had varying amounts of research done on them, which this repository captures.

This repository contains:

* county-level [**DATA**](DATA)/\<county-name\> folders holding two files per leftover rainfall sheet:
  * an image of each rainfall sheet, extracted from [the Met Office Digital Library and Archive](https://digital.nmla.metoffice.gov.uk/index.php?name=SO_d383374a-91c3-4a7b-ba96-41b81cfb9d67)
  * a CSV file per image, recording the monthly rainfall figures transcribed by Rainfall Rescue volunteers; some of these figures may be estimates
  * note that the leftover sheets for sites now in the Republic of Ireland are held under a different repository: [rainfall-rescue-data-eire/LEFT-OVER](https://github.com/ed-hawkins/rainfall-rescue-data-eire/tree/main/LEFT-OVER)
  
* the [**LeftOverSheets spreadsheet**](LeftOverSheets.xlsx), which has a row per leftover rainfall sheet recording what is known about the sheet:
	* a summary of the information from the sheet's CSV transcription file
	* a site name, allowing related leftover sheets to be grouped together
	* a UK National Grid Reference, if one has been determined - possibly only an approximate location 
	* other metadata (elevation, station number, observer) from the rainfall sheet, if captured
	* a comment to record any other details researched
* the [**LeftOverSites spreadsheet**](LeftOverSites.xlsx) provides similar information, but with a row per site name, combining the the leftover rainfall sheets assigned to each site name

