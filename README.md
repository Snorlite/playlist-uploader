# playlist-uploader
Script to automatically add videos from a Youtube channel to a user playlist

Once specified a Youtube channel as input and a playlist as output, it gives the option to add videos in chronological order (starting from a page token, since the API returns max 50 videos per request; if no page token is specified it starts from the newest videos).

There's also an option to add videos specifying the IDs directly.

The HTML must be started in a running web server environment like node.js, since the Google Sign In API won't work otherwise.

![image](https://github.com/Snorlite/playlist-uploader/assets/42011697/18b8cf10-4a2e-488e-85bd-53374a1208c9)
