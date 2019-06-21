# BetterSoundCloud

BetterSoundCloud (BSC) is an open source project to improve the usability of the SoundCloud browser interface. The project is primarily concerned with parsing, filtering, and collating SoundCloud items, whether they are tracks or playlists, and then presenting them in a way that is more intuitive for the user.

BSC can hide or remove tracks depending on the following criteria:
* Minimum track duration
* Maximum track duration
* If it is a repost
* If it is a promoted post
* If it is a playlist
* If it is on your stream or a user's profile
* If it is a repost from a blocked user

The platform is quite extensible and custom filters can be written fairly easily to perform other DOM related operations to the feed.


## Prerequisites

This is a Chrome extension, so the only prerequisite is having Chrome installed.


## Installing

This version is not available in the Chrome web store, so you'll have to load it as a local extension.

To do this, you must first download the files from the GitHub repository: click the green "Clone or download" button then "Download ZIP."

Next, find a cozy location for this extension to live on your hard drive (or leave it wherever it was downloaded to) and then unzip the file.

Now, open Chrome and follow these directions: click "Window" in the top menu > click "Extensions" > click "Load Unpacked" > in the file directory modal, locate your unzipped BetterSoundCloud folder and then click into the "public_html" subfolder > click "Select" > that's it!

If those instructions are unclear or if you run into other trouble, you can find more information on loading local extensions [here](https://developer.chrome.com/extensions/getstarted#unpacked).


## Usage Instructions

Simply click the orange dot to the right of the URL field and then click the "Filter Settings" button. On the settings page, you can set whichever filters you prefer.


## Authors

* **Brian Cefali** - *Initial work* - [Brocef](https://github.com/brocef)

See also the list of [contributors](https://github.com/brocef/BetterSoundCloud/contributors) who participated in this project.

This version modified by [KWS](https://www.kevinwadeshaw.com/) for a better BetterSoundCloud experience  🧡


## License

This project is licensed under the GNU 3 License - see the [LICENSE.md](LICENSE.md) file for details.


## Acknowledgments

* Luke for help with silly JavaScript "features"
* Shane, Alexis for help with early testing
