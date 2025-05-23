# Website-With-Login-Templet

  ✅ 1. Initialize the project 

Run this in Terminal

    npm init -y

    
   ✅ 2. Install Packages 

Run this in Terminal

    npm install express cors cookie-parser

✅ 3. Create app.js

Write this in app.js

    const express = require('express');
    const app = express();
    const cors = require('cors');
    const cookieParser = require('cookie-parser');
    const port = 3000;


    // Serve static files (HTML, CSS, JS)
    app.use(express.static('public'));


    // Checks if the server is running
    app.listen(port, () => {
    console.log(`Server running at http://localhost:${port}`);
    });

✅ 4. Test if everything is working

Run this in Terminal

    node app.js
