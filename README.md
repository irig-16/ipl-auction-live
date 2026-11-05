# IPL Auction Live

A live cricket auction party game for 2 to 4 franchises, one phone each. Everyone gets the same purse, bids in real auction steps under an overseas limit, then plays a full league season with a final.

**Play now:** https://cric-auction.netlify.app/

## Play

Play at https://cric-auction.netlify.app/, open `index.html` in a browser, or host it yourself with GitHub Pages or Netlify.

1. One player taps **Host an auction** and shares the 4-letter code, invite link or QR.
2. Friends open the same page on their phones and join with the code.
3. The host can add computer franchises (Easy, Sharp or Ruthless) to fill the table.

## Features

- 81-player pool in sets: Marquee, Batters, Keepers, All-rounders, Pace, Spin and Uncapped.
- Settings for squad size, purse, hammer timer, player list and match luck.
- A math-based computer bidder that values each player by how much they improve its best XI.
- An over-by-over season with net run rate, points table, Orange Cap and Purple Cap.
- Voice chat, reactions, sounds, vibration on Android, and a photo studio for player pictures.

## How it works

It's one self-contained HTML file. Devices connect peer to peer over WebRTC using [PeerJS](https://peerjs.com) and its free public broker. There's no backend, and the host's phone runs the game.

Player ratings are game ratings, not official figures. The game isn't affiliated with the IPL, BCCI or any franchise.

## Third-party code

- PeerJS 1.5.5 (MIT)
- qrcode-generator 1.4.4 (MIT, Kazuhiko Arase)
