# Music Dices

To install the application (requires `node.js` and optionally `git`):
* check out the repository using `git` or download and unzip the code
* open a shell/terminal and change the current directory to the downloaded (unzipped) `music-dices` project directory
* run `npm install`

To run the application:
* run `npm run watch` in the `GemMus-2018` project directory in an open a shell/terminal
* to start a `player` client, open the URL `localhost:8000` in your browser
* to start the `controller` client, open the URL `localhost:8000/controller` in your browser

To run the `sensor` client on your mobile device you have to connect to the same network as the server and open `<server address>:8000/sensor` in a browser on the mobile device. For the `display`-client use `<server address>:8000/display`. The controller-client allows for changeing some parameters `<server address>:8000/controller`.
