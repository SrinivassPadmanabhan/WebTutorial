#Utility For IndexedDB 

IndexedDB:
IndexedDB is a low-level API for client-side storage of significant amounts of structured data, including files/blobs. This API uses indexes to enable high-performance searches of this data. While Web Storage is useful for storing smaller amounts of data, it is less useful for storing larger amounts of structured data. IndexedDB provides a solution. This is the main landing page for MDN's IndexedDB coverage — here we provide links to the full API reference and usage guides, browser support details, and some explanation of key concepts.(Reference MDN 
For more Details
link: https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)

Prerequisites:
		To run this Project It need a Server and any browser that Supports Indexed DB(Chrome version greater than 23, safari greater than 10, Opera greater than 15, Edge greater than 12 partially support and IE greater than 10 Partially support)
		To Start the Server, you can use the Python(https://www.python.org/downloads/)based on your OS version you can download from the above link OR 
		You can use the Chrome WEB APP (https://chrome.google.com/webstore/detail/web-server-for-chrome/ofhbbkphhbklhfoeikjpcbhemlocgigb?hl=en) this is just a button click to start the server by specifying the Folder

Example:

The Example is mentioned in the HTML page

In the Utility File you can use the 

setDBDetails:
This function is used for Setting the DB details, for the Adding the table and the Indexes for the Tables
OpenDatabase:
This function is used for Opening the Database for the Whole Project Purpose
put :
This Function is used for the Putting the multiple Values in the Database at a time
get: 
This Function is used for the Getting the multiple Values from the Database 

asynChronousOPeration class:
This class is mainly for handling the asynchronous Looping purpose
To execute in the Same order the Values which are given after every success of the Previous Asynchronous call this will get executed

TestCase: you can use the IndexedDB.html page for testing purpose
