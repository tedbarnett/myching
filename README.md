# MyChing
A Node-RED flow for the Amazon Alexa skill "My Ching", created by Barnett Labs LLC.  It uses Node-RED running on IBM's Bluemix, with a Cloudant database.  A screenshot of the flow is attached as [myching_flow.png](https://github.com/tedbarnett/myching/blob/master/myching_flow.PNG).

A few notes:
- A helpful "Hello World" tutorial on using Node-RED to build Alexa (Echo) apps: https://www.youtube.com/watch?v=bt26Tnhdu80
- Node-RED documentation: http://nodered.org/docs/
- For Amazon Echo certification, this app relies on the node "alexa-verifier" created by Mike Reinstein (https://github.com/mreinstein/alexa-verifier)
- The app's data resides in 3 Cloudant NoSQL databases: hexagrams (a table of the actual hexagrams), users (tracking user visits), and feedback (collecting user feedback scores) 

You can install this app on your Amazon Echo by saying "Alexa, enable My Ching".

Contact ted (at) barnettlabs.com with any questions.
