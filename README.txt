# User Modeling Node.js Starter Application


## Files

The User Modeling Node.js starter application has files as below:


*   app.js

	This file contains the server side JavaScript code for your application written using the Node.js API

*   views/

	This directory contains the views of the application. It is required by the express framework and jade template engine in this sample application.

*   public/

	This directory contains public resources of the application. It is required by the express framework in this sample application.

*   package.json

	This file is required by the Node.js environment. It specifies this Node.js project name, dependencies, and other configurations of your Node.js application.

## Analyzing Logs

* Please note that this only (reliably) analyzes _weechat_ logs at the moment. By changing the slice indices you canadjust accordingly for your logs.

Put the logfile in the correct folder then reference it in ``app.js``. Then push it upstream using cloudflare and go to the designated url to see your application in action! Just type in the name of someone in the logs to analyze their personality!
