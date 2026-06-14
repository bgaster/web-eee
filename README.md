![](docs/images/diii.png)

# eee 

A web-based live-coding and management interface for eee devices

Send commands, get text feedback, and manage the files on your eee device.

This repo has the source code for this static web app. For docs, go [here](https://cuberoo.uk/docs/eee/deee).

This webapp is built from [web-diii](https://github.com/monome/web-diii). This project has nothing to do with [monome.org][https://monome.org], although their work is amazing and inspiring. Of course, we retain their GPL 3.0 license and this work is open to everyone.

## requirements

Uses the Web Serial API that is only available in chromium-based browsers like Chrome, Chromium, Edge, and Opera.

Can be installed as a progressive web app via the install app button in the browser address bar, allowing for use without an internet connection.

## a note for web developers

to run locally for development on the site itself, run this in the web-eee root directory then browse to localhost:8000
```bash
python3 -m http.server 8000
```

This is **not** necessary for using eee offline, see the note above about installing as a progressive web app for the best experience there.
