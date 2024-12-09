# Open video in mpv-android addon

Open any video with your favorite Android video player! Thanks to this extension you will be able to open online videos with mpv.  
It will set og:title or title of the website as the title for the video.

**Addon for Firefox for Android v56+**    

## Developing

Use web-ext cli tool:

```
npm install --global web-ext
```

Then:

```
web-ext run --target=firefox-android
```

When satisfied build the installable zip:

```
web-ext build
```

(You might need to enable debug menu by tapping Firefox logo in "About Firefox" multiple times to be able to install this)  
(Fuck Mozilla... Icecraven allows the user to open about:config and then to set xpinstall.signatures.required to false)  

# TODO
- Set badge to show number of links or streaming site name when a link is detected  
- Support more streaming sites (e.g. send-to-mpv supports more but doesn't work on Android)
