###Baring Family Art Sales/Purchases
Based on _Art Sales from early in the eighteenth century to early in the twentiety century (mostly old master and early English pictures)_ by Algernon Graves, F.S.A.
Published 1918-1921 in 3 Vols. 

###What is this? 
_Art Sales_ provides a structured listing of art sales that happened in London, England, between the late 18th century (1791ish) to the early 20th century (1908ish). 

The book lists results by artist name, then sales chronologically by year, month and date. 

This is an extraction of that data in to **CSV** and **JSON** data formats. The data is being made available for curiosity and fun. 

###Why is this important?	
The data contained in Graves is a important for the study of provenance, but could also be used to do a larger network analysis on who was buying what, for how much, and from who. 

###Scope of data
The included data follows the Baring family, because of a IMLS/NEH/Kress funded research project at Carnegie Museum of Art. Read more about that [here](http://blog.cmoa.org/category/art-tracks/), and check out our work on GitHub [here](http://github.com/cmoa). 

So the data is limited in scope. I went through all 1000+ pages of data looking for the Francis Baring and Thomas Baring in both purchases and sales columns, and recorded and flagged that data. 

What would be really useful is if this data could grow to include the entirity of the Art Sales book. You can find the first volume of the book online [here](https://babel.hathitrust.org/cgi/pt?id=njp.32101067589935). Vols. 2 & 3 are not currently online, but may be requested through a local library, likely through interlibrary loan- but check [WorldCat](http://www.worldcat.org/title/art-sales-from-early-in-the-eighteenth-century-to-early-in-the-twentieth-century-mostly-old-master-and-early-english-pictures/oclc/17488229&referer=brief_results) first. 

###Data Structure

#####Headings
`"artist"`: "Backhuysen, Ludolf",  (who made the item)  
`"date_year"`: 1848, (year of auction)   
`"date_month"`: "June",  (month of auction)  
`"date_day"`: 2,  (day of acution)  
`"auctioneer"`: "Christie's",  (place of auction or auctioneer)  
`"owner"`: "Sir Thomas Baring",  (who is offering the item for sale)  
`"lot number"`: 130,  (lot number assigned to the item)  
`"title"`: "Fresh Breeze",  (title assigned to item)  
`"dim_height"`: 0, (height of item, in inches, **if recorded**)  
`"dim_width"`: 0,  (width of item, in inches **if recorded**)  
`"purchaser"`: "Nieuwenhuys", (purchaser of item, **if recorded**)   
`"pounds"`: 283, (price paid, pounds)   
`"shillings"`: 10,  (price paid, shillings)  
`"pence"`: 0 (price paid, pence)  


###Can I contribute? 
Sure!

Found an error? Send me a pull request. Cheers. 

Want to transcribe the rest of the data--not limited to the Barings? You. are. **awesome**. Clone this repo, add the stuff, and send me a pull request. Enjoy endless good art history karma. 

###What can I do with this?
Anything you want. Nothing. Everything. 

CC-0, and what have you. 

It'd be nice if you ref'd this repo if you end up doing something cool with it, but not necessary. Data wants to be free. 

###Disclosures, etc.
Use this data at your own risk. I've done by best to make it acurate, but I cannot swear or guarentee its acuracy. Please use your best judgement before basing a thesis on it. 




 