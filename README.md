Node Music Player
=================
#### An open source web-based music player

![alt tag](https://f.cloud.github.com/assets/608054/2256870/25a93a38-9e0e-11e3-8432-b0cc2e2c896f.png)

### How does it work?
Run it on your computer or server containing your music library and then access it through `<ip of computer>:2000`, for example if you run it on your local computer you would use `localhost:2000`.

### Installation Instructions
##### Dependencies
[node](http://nodejs.org/), [git](http://git-scm.com/)

Install with the following commands:
```
git clone git@github.com:benkaiser/node-music-player.git
cd node-music-player/
npm install
```
Edit the `config.js` file and set `music_dir` to be the folder you want to be scanned for your music.

Then run the server with:
```
node app.js
```
Go to `localhost:2000` in your browser (or known ip of server if it is on a different machine). From there click the `Scan Library` tab at the top of the page. From there select `Start Scan` and let it do it's magic. Once your library is scanned you should be able to access it from the `Music` tab up the top.

### Features Implemented

- Play songs and move between tracks
- View full-resolution cover art
- Full playlist support
- Multiple selection
- Repeat, repeat one and shuffle
- Search functionality

### Short-Term planned features

- Cross-device syncing over network (between computers and android devices)
- Remote controlling from other devices (i.e. phones, tablets, other computers)
- Mobile viewing, so one may play and listen their library in an intuitive interface for a mobile phone
- Favourite artists section