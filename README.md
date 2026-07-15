# Personal Music Listening Device
### What?
The title is quite self-explanatory. I would like to make my own high-enough fidelity music player for completely offline listening without the standard outages of Spotify.

### Why?
Of late, there have been many outages in cloud-based services, e.g Spotify literally every week, the big aws-east-1 outage, and so on. Maintenace, negligence or self-done sabotage, you decide. But one thing I saw was the volatility of it all.
Hence, I have decided to go the mostly-offline way. 

### How?
I have a component list in mind. Thank god for other similar-minded hobbyists.

- Main compute : Raspberry Pi Zero 2 W, 512MiB RAM
- Storage : 512GB Sandisk Extreme for fast R/W, ideally store ~18K FLAC or ~98K 320K MP3s.
- Audio Interface and Screen : Pimoroni Pirate Audio
- Battery : PiSugar 3 or something equivalent

I have some software that I'd like to make too. 
- SQLite DB on storage for caching listening data, nice analytics page to show the same. (could also use mpdscribble but oh well)
- Possible logging bridge between the analytics page and lastfm, if possible.

### When?
When I have the money for the components.

