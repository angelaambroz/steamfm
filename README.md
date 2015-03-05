last-steam
=======

5 March 2015. The [last.fm API](http://www.last.fm/api) was too fun to not use again. A steamgraph, inspired by [Lee Byron's project](http://www.leebyron.com/what/lastfm/), to explore your genre listening habits (as measured in minutes listened, rather than "plays"). This will also compare your steamgraph to your "neighborhood" (friends' aggregated listening habits).

### A bit more detail on what I'm thinking

* Weekly listening habits
* Updated automatically (using `Date.now()`? or some other time thing)
* Though you can also scroll horizontally to older weeks...


### To Do
1. ~~Get this thing going! `git init`, adapting the `lastfm.html`, etc.~~
2. Find a way to use [this wonderful gobliny font](https://www.google.com/fonts/specimen/Astloch).
3. ~~Figure out data I'll need.~~
4. Re-understand `.queue`!
5. Why are the track `mbid`s not working?
6. ~~Replace `mbid`s with artist/song names.~~
7. `.queue` is failing when any of the (many!) calls fail. How do prevent/accommodate this?


### Resources

* API info: [last.fm - user.getTopArtists](http://www.last.fm/api/show/user.getTopArtists)



