###Graves Art Sale Data
Based on _Art Sales from early in the eighteenth century to early in the twentiety century (mostly old master and early English pictures)_ by Algernon Graves, F.S.A.
Published 1918-1921 in 3 Vols. 

###What is this? 
_Art Sales_ provides a structured listing of art sales that happened in London, England, between the late 18th century (1791ish) to the early 20th century (1917ish). 

The book lists results by artist name, then sales chronologically by year, month and date. 

This is an extraction of that data in to **CSV** and **JSON** data formats. The data is being made available for curiosity and fun. 

###Why is this important?	
The data contained in Graves is a important for the study of provenance, but could also be used to do a larger network analysis on who was buying what, for how much, and from who. 

###Scope of data
The included data was initiated to track the purchasing activity of the Baring family, later to include the [Earls of Northbrook](https://en.wikipedia.org/wiki/Thomas_Baring,_1st_Earl_of_Northbrook), as part of a IMLS/NEH/Kress funded research project at Carnegie Museum of Art. Read more about that [here](http://blog.cmoa.org/category/art-tracks/), and check out our work on GitHub [here](http://github.com/cmoa). 


~~What would be really useful is if this data could grow to include the entirity of the Art Sales book. You can find the first volume of the book online [here](https://babel.hathitrust.org/cgi/pt?id=njp.32101067589935). Vols. 2 & 3 are not currently online, but may be requested through a local library, likely through interlibrary loan- but check [WorldCat](http://www.worldcat.org/title/art-sales-from-early-in-the-eighteenth-century-to-early-in-the-twentieth-century-mostly-old-master-and-early-english-pictures/oclc/17488229&referer=brief_results) first.~~

The first volume of _Art Sales_ is available through the [InternetArchive](https://archive.org/details/GravesArtSalesVolumeOne). 

This data was obtained by scanning the second and third volumes of _Art Sales_ in a book scanner with Optical Character Recognition (OCR) software. The first volume was already available in PDF format. The data was then extracted to `xls` format using ABBYY FineReader Pro, and then cleaned and  exported to `.csv` and `.json` formats. 


###Data Structure

#####Headings
`"artist"`: "Backhuysen, Ludolf",  (who made the item)  
`"year"`: 1848, (year of auction)   
`"month_day"`: "June 2",  (month and date of auction)    
`"auctioneer"`: "Christie's",  "Paris" (place of auction or auctioneer)  
`"seller"`: "Sir Thomas Baring",  (who is offering the item for sale)  
`"title"`: "Fresh Breeze",  (title assigned to item)   
`"purchaser"`: "Nieuwenhuys", (purchaser of item, **if recorded**)   
`"pounds"`: 283, (price paid, pounds)   
`"shillings"`: 10,  (price paid, shillings)  
`"pence"`: 0 (price paid, pence)  

###Unresolved Problems
Check out the issues tickets for known issues with this data. 

As of July 25, 2016, the biggest known issues are:  
1) The need to write scripts to extract ``"seller"`` names from the front of artwork titles.   
2) Troubles in modeling data where items were sold "en bloc". (i.e. a purchases bought paintings x, y, and z at the same auction on the same day for one price, rather than buying x, y, and z as separate units, with their own purchase prices. 


###Can I contribute? 
Sure!

Found an error? Send a pull request. Cheers. 

Want to transcribe the rest of the data--not limited to the Barings? You. are. **awesome**. Clone this repo, add the stuff, and send me a pull request. Enjoy endless good art history karma. 

###What can I do with this?
Anything you want. Nothing. Everything. 

CC-0, and what have you. 

It'd be nice if you ref'd this repo if you end up doing something cool with it, but not necessary. Data wants to be free. 

###What's up with the `Baring_only` file?
The data contained in this file is related to the purchases of the Baring family. It's a much smaller pool of records, related to the art purchasing and selling activities of the Baring (Northbrook) families. You're welcome to use this data too, but it is much more limited in scope. 

###Disclosures, etc.
Use this data at your own risk. I've done by best to make it acurate, but I cannot swear or guarentee its acuracy. Please use your best judgement before basing a thesis on it. 

###Who created this? Who contributed? 
This data set was scanned, cleaned, and harvested by [Tracey Berg-Fulton](https://github.com/bergfulton). As Tracey is a human and had to do a lot of the data cleaning by hand w/software assistance, the data is likely not perfect. 



 
