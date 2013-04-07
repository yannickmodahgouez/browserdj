# BrowserDJ - A Web Browser DJ Mixer

The BrowserDJ is an open-source web browser DJ mixer.

![Screeb](./assets/screen.png)
## Installation

You can use BrowserDJ as an offline web application or Node.js application.

### Offline web application

1. Download BrowserDJ at the terminal:

        $ git clone https://github.com/sodesign/browserdj

2. Open the `public/index.html` file and you will see the UI:

        $ open browserdj/public/index.html


### Node.js web application

1. Download BrowserDJ at the terminal:

        $ git clone https://github.com/sodesign/browserdj

2. Install npm package:

        $ cd browserdj
        $ npm install

3. Start node.js application:

        $ node app.js

4. Open `http://localhost:3000`.



## Usage

1. Click a "Load" button.

2. Select your local music file in the file dialog.  (e.g. mp3, .m4u)

3. Click a "Play" button.


## TODO

Because BrowserDJ is just a sample application for the WebAudio API, it provides very limited functionality compared to other PCDJ software. 

There are a lot of tasks we have to do. 

- Hi-Mid-Low EQ.

- Effects

- Peformance improvement

- Error handling

- Testing

- Bug fixing

- Multi-user online play using websocket



## License

BrowserDJ is released under the [MIT](http://opensource.org/licenses/MIT) license.





