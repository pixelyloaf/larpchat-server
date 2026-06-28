<h1 align="center">Welcome to the larpchat repository </h1>
This is the server for Larpchat.<br>
For clients and stuff, see the <a href="https://github.com/Unitendo/aurorachat">main repo</a>.
The license, code of conduct, and security/contributing guidelines in the main repo also apply here.

<br>This repository is **open** for contributions! If you'd like to, you may open a PR or an issue, contributing helps us as we develop larpchat!

## How to Run the Server ##

### Running LUC v6 ###

```bash
git clone https://github.com/pixelyloaf/larpchat-server.git
cd larpchat-server

# Install dependencies
npm install express express-session bcryptjs jsonwebtoken

# Setup server configuration
cp config.example.js config.js
# Now would be a great time to edit config.js

node server.js
```
