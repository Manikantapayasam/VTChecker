# VTChecker
The excel is used to get the bulk domains, hashes and urls from VirusTotal using an API


Instructions to use:

	1) Enter your VirusTotal API key in API sheet 1st cell ( i.e., A1 column)
	
	2) For Domains:
		Enter the domains list in the Domains sheet
			Note: Domain should not contain http,https,www or any url part
			Example Domain's : google.com, docs.google.com, facebook.com
		Click the Run button once you entered the data in Domain sheet

	3) For URLS:
		Enter the URL's list in the URLS sheet
		Click the Run button once you entered the data in URL sheet
		
	4) For Hashes: 
		Enter the hashes list in the Hashes sheet
		Click the Run button once you entered the data in Hashes sheet

Limitations:

	1)  It will run 4 queries per minute and max 1K prequests per day.
	
	2) This is designed for VirusTotal public api-key , don't know whether it will work for premium key.
	
	3) If you want to re-run the particular task then you should clear all the results otherwise it dislays a message "completed".
	
	4) Don't give any blank row between the data because the blank row is considered as a End of the Data
	
	
Resources: 

https://github.com/VBA-tools/VBA-JSON
		

