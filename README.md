githubplaysgameboy
==================

Multiplayer GameBoy emulator using HTML5, socket.io and node.js.
You can host the server on Herokuapp easily (Procfile included) and it works pretty well !

![illustation](https://googledrive.com/host/0B71TAoXLSxy6VEVvRE4yN3JtRGs/bpgb.png)

**DISCLAIMER**

You must own a legal .gb rom in order to use this.

How to use
----------

First, edit *config.json* in order to make this work.

* port: Port number for the server (env.PORT is prioritary) (default: 3000)
* url: URL with the IP of the server (default: http://127.0.0.1)
* allowed_inputs: Specify wich inputs are allowed. (default: basic GameBoy inputs)
* rom: File name for your GameBoy rom. Relative path (default: 'rom.gb')

Install modules

`npm install`

Launch the server

`node app.js`

You are ready to go !

For the "master", launch a browser with `[YOUR_URL]:[YOUR_PORT]/master` (default: http://127.0.0.1:3000/master).
For a controller, launch a browser with `[YOUR_URL]:[YOUR_PORT]/` (default: http://127.0.0.1:3000).

Special thanks
--------------

grantgalitz for his [GameBoy Online emulator](https://github.com/grantgalitz/GameBoy-Online).