# Overview
This is a new MERN based application for building some APIs and rendering a frontend from that data.

# Technologies used
This is pretty basic. It just runs node with express and connects to MongoDB (Atlas) whhich I have signed up for a test account. The React side is actually using something i've never used before - Vite. Grabbed a few example screenshots, etc. and put them together.

# How to use
There are two folders
1. client
2. server

Open up two terminals, one inside each folder.

For the `server` side run the command `node --env-file=config.env server`. You will need to create a `config.env` in the root /server folder which is where I put mine. It has my ATLAS_URI (add your own) and PORT is set to 5050.

for the `client` side just `npm run dev`.

And that's it!