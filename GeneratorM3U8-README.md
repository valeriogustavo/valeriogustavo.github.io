# [Generator M3U8](https://github.com/valeriogustavo/valeriogustavo.github.io/blob/main/GeneratorM3U8)
By Gustavo Valério -> www.gustavovalerio.com.br

Go to Script -> [CLICK](https://github.com/valeriogustavo/valeriogustavo.github.io/blob/main/GeneratorM3U8)



Generate your m3u8 playlists from organized files.


* Change the LOCAL_URL to your LOCAL IP (use hostname -I).
* If you are not going to use a public list with a different URL, set ENABLE_LIST_PUBLIC to False.
* To use a public list with a URL other than URL_LOCAL, keep ENABLE_LIST_PUBLIC True and set URL_PUBLIC pointing to the correct domain.
* It is necessary to have FFMPEG installed on the machine for the script to work properly.



# Setting up a directory for Movies


The correct structure, so that the covers are used correctly, should look like this:

  * Inside your movie directory there should be a hidden directory called "covers". 
  * The extension of the covers must be "jpg". JPEG, PNG or others will not work.  
  * The covers inside the "covers" directory must have the exact same name as the movie to which it belongs, which is in the top directory.  
  * Movies must be in "mkv" format. This format was chosen because it is possible to transmit several subtitles and audios in the same file.

![Movies](https://user-images.githubusercontent.com/9014758/136222345-1b4558c4-1790-40f1-b95c-30822d33ddd3.png)
 
# Setting up a directory for your favorite series
* The "Series" directory will contain all series directories.
* Each series directory must contain the directories of their respective seasons.
* Each season directory must contain a hidden "jpg" file named ".cover.jpg". This file is the cover of the season it belongs to.
* The ".cover.jpg" file will be used as the cover for all episodes of the same season.
* Episodes can have any name. Its extension must be MKV, the extension chosen because it allows the transmission of several subtitles and audio files.

![Series](https://github.com/valeriogustavo/valeriogustavo.github.io/blob/main/images/Series.jpg)
