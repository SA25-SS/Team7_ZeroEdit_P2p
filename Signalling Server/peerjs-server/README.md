# PeerServer: A server for PeerJS

PeerServer helps establishing connections between PeerJS clients.



## Usage

### Run server



1. Install the package:

   ```bash
   # $ cd your-project-path

   # with npm
   $ npm install peer

   # with yarn
   $ yarn add peer
   ```

2. Use PeerServer object to create a new server:

   ```javascript
   const { PeerServer } = require("peer");

   const peerServer = PeerServer({ port: 9000, path: "/myapp" });
   ```

3. Check it: http://127.0.0.1:9000/myapp It should returns JSON with name, description and website fields.

