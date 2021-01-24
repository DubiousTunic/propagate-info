# propagate-info
private torrent trackers in the browser
There are two ajax calls in the code, modify them to your own custom JSONblob URL and propagate info

What is it?
This is meant to be Gazelle for the browser. It runs on WebTorrent to distribute user uploaded torrents which are stored in a "bitchain." I might switch this to a crypto solution. The Bitchain uses jsonblob.com to store the last uploaded torrent infoHash. This infoHash connects WebTorrent to a torrent file whose metadata points to the infoHash of the last upload before that, etc.

link to html file a redirect from pharaoh.ninja
