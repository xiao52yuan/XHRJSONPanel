# XHRJSONPanel
Chrome Dev Tools extension for XHR JSON based requests. 


This extension add to Chrome Dev Tools a new XHR JSON Panel that presents the most important data sent/received in an Ajax process.

The extension presents a list with all XHR request made to server that have 'application/json' as content type. When expanding the details of such request by clicking + icon, two panel will appear below the request url. On the left side there will be the response preview and on the right side the GET parameters that are attached to the request URL ( good to view and quick to read for long URLs) and below of this the  POST payload data if any ( and of course, if the request method is POST).
This extension is inspired by Firebug console and helps me when I need to quick compare the data from more requests. In Chrome Dev Tools Network panel I can see the data for only one request at a time.  
