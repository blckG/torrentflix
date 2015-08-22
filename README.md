# Torrentflix

Forked torrentflix with the goal of using it's torrent searching libraries as a torrent
searching module that can have it's results parsed programmatically.

It currently supports kickasstorrents, 1337x, seedpeer, Rarbg, The Pirate Bay, YTS, Extratorrent, Limetorrents, nyaa.se & tokyotosho.

Want more ? Create an issue with a request, Alternatively you can contribute your own scrapers.

Pull requests are welcome.

## Key features

*  Subtitles fetched automatically.
*  History of streamed torrents.


## Install (manual)
Install peerflix if you haven't already:

```
npm install -g peerflix
```

Clone the repository:

```
git clone git@github.com:ItzBlitz98/torrentflix.git
```

Install dependencies:

```
npm install
```

You can now update by doing a git pull:

```
git pull
```

Now you can run the executable inside the bin folder.

## Preview
A short video preview: http://webm.host/365df/vid.webm

![peerflix](https://i.imgur.com/rre0MtK.png)

## Usage
To run the app run:
```
$ torrentflix
```

## History
Torrentflix can save a history of watched torrents if enabled.

Clearing the history can be done with the --clear flag ex:
```
$ torrentflix --clear
```

## Subtitles
Torrentflix supports subtitles, By default subtitles are disabled you can enable them by running the config command above.
You can also change the subtitle language from the config.


## License

MIT
