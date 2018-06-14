# About this extension

This is an assignment project for Coventry University Open Source Development Course<br>
by Isabel Tiong. <br>
### Definition
This is a Youtube **Audio only** playlist player that allows you to simply create your audio track from youtube videos link<br>

### Screenshot
![alt text](https://github.com/isabeltiongsk/youtubeAudioPlaylist.mz-extension/blob/master/demo.JPG) <br>

### Demo
PLEASE NOTICE THAT THIS FEATURE CAN ONLY RUN ON **FIREFOX BROWSER**<br>
You can try the [Demo](http://htmlpreview.github.io/?https://github.com/isabeltiongsk/youtubeAudioPlaylist.mz-extension/blob/master/index.html) here

## About youtube playlist/ features
The main objectives while building this extension is to make a simple youtube audio only player, which save battery of your device since it does not display the video itself.<br>
Then I decided to make a playlist instead, where you can just simply key in the youtube id for the playlist. So that no login and then create a new playlist is required if you are a person who like to listen to different music. <br>
No redirecting back to the Youtube tab for the next song and most importantly NO Ads!

                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           
### How to install extension to play
* Download all codes from master branch
* Extract files to local if you downloaded the zip file
* Open firefox browser
* Go to **'about:debugging'**
* Press the **'Load Temporary Add-on'** button
* Select the **'manifest.json'** file
* Game icon will appeared on the right side bar.
* Press it and the popup window will show

<br>

### How to use the YT audio player
* If you succeed to install the extension, you will see this page. <br>
![demo](https://github.com/isabeltiongsk/youtubeAudioPlaylist.mz-extension/blob/master/demo.JPG) <br> <br>
* In the input field, just paste your youtube id. <br> 
![demo](https://github.com/isabeltiongsk/youtubeAudioPlaylist.mz-extension/blob/master/demo/demo-1.JPG) <br> <br>
* The id is the value behind the 'v=' of the youtube url. <br>
![demo](https://github.com/isabeltiongsk/youtubeAudioPlaylist.mz-extension/blob/master/demo/demo-2.JPG) <br> <br>
* When you paste in your id, simply press the 'Start Playlist' button and enjoy your music!<br>
![demo](https://github.com/isabeltiongsk/youtubeAudioPlaylist.mz-extension/blob/master/demo/demo-3.JPG) <br> <br>
* The audio timeline and volume line will show up when the playlist played successfuly. You can then adjust the volume with both the bar or entering your desired volume value. <br>
![demo](https://github.com/isabeltiongsk/youtubeAudioPlaylist.mz-extension/blob/master/demo/demo-4.JPG) <br> <br>

## Extension Not Working?
There has been several errors conducted for this features as the Content Security Policy from Firefox districted parts of the YoutubeApi scripts. Although I added the CSP header to prevent it from blocking, errors might still occured due to mozilla version or some plugin that will enabled the headers. <br>

### Frequent error that might happened: audio is not playing
First thing first, check if you downloaded EVERYTHING from the master branch. <br>
Run the **'index.html'** file **ON A FIREFOX BROWSER** to check if it is working.  Please do not use NetBeans IDE to run the file as there is some bug that block the CSP, and this is yet not solved.<br><br>

If the html can run and the playlist is functioning, <br>
<br>
Check if you are using any **Ad blocker extension** on your browser. If you do, disable it and reload the extenssion again. <br>

If there is still an error, check whether your using a firefox browser that is above version 58. <br>

That should be it for solving the error.

## Code References

The source code I referred for this feature is from [Jemillol](https://github.com/JemiloII/Youtube-Audio-Player) for his audio player's css files. 
<br>
All the below features are then added 
* Input data field
* Get snipple tittle
* Play next Youtube audio when ended
* Call playlist function onClick


