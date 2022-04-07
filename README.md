# webhook-listener
Utility for displaying the contents of post requests

Run this on the public internet and the root page displays the contents of a JSON body posted to the /hook endpoint with content-type: application/json. 

Refresh the page to see new posts. 

Posts are not persisted between restarts -  if you restart the application all history is lost. 
