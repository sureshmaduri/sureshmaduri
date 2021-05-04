-File compare 
Sort File and make sure count and folder are matching.
Then start comparing file.
Extract XML Template XML & Test XML
Check TemplateXML  first--> 
If TradeNotification yes 
Then check Order count if matches
  Then check Allocation count  if matches 
     Then check Element presense in order 
	      first look for any element not in template 
		  second look for any element not in Test
	   Then check Element present in Alloc
	      first look for any element not in template 
		  second look for any element not in Test
Log if any difference
Loop thru the entire file.
