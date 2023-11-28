# REST_API_gsheets
Creating a simple REST API from Google Sheets and hosting it on Google Cloud

ContentService: It's a class in Google Apps Script that provides the ability 
to serve and handle different types of content.

createTextOutput(): This method creates a text-based output object. 
It's used to create a response object that will contain the data in text format.

JSON.stringify({data: output}): The JSON.stringify() method converts a JavaScript object 
or value into a JSON string representation

.setMimeType(ContentService.MimeType.JSON): This method sets the 
MIME type (Multipurpose Internet Mail Extensions type) of the content. 

ContentService.MimeType.JSON specifies that the content being served is in JSON format. 
This MIME type helps the client/browser understand the type of data being returned.
