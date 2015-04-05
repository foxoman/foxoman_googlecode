## DivX Converter 2.0 final ##
## Important ##

if you can not start the application run this command in the terminal and try again

```
sudo chmod -R +r /usr/share/divx-converter/ 
```

Thanks to  ezaffa and  apiemont and to you all :)

## Description and Overview ##

DivX converter is a simple Mencoder frontend to Produce DivX Player Compatible AVI video format with the ability to merge subtitles . It support many video and audio filters and many presets.

### List Of Feature : ###
  1. Clean and Easy Interface
  1. Convert variety type of video format to avi
  1. Support DivX 4/5 , H.264 and Xvid Video codecs
  1. Support MP3, AC3 and ACC audio codecs
  1. You can merge your subtitle to your favorite video, with many Language Encoding support .
  1. Multifile conversion
  1. Screenshot and use-full information about the file being convert
  1. 9 quality preset
  1. Many video and audio filters
  1. Multi-Core threading support

## New in 2.0 final ##

  * Help manual
  * GUI and encoding optimized
  * a few bug fixing
  * spanish translation

## New in v 2.0 RC 3 ##


divxconverter (2.0-rc3) experimental; urgency=high

  * New easy look [inteface](new.md)
  * Add alpha black background [subtitle](subtitle.md)
  * Add sample rate [filters](Audio.md)
  * Add Harddup and softskip [Filters](Video.md)
  * add Postprocessing filters [filters](video.md)
  * add HQ denoiser filter[filters](video.md)
  * fixing a few bugs -)
  * Multi-Language support [english and arabic ](.md) [Your language ? Download the .pot file and translate it to your language for the final relaese.!
  * hope to be the last RC before the final


## New in V 2.0 RC 2 ##

  * Quik Fix Fix application path not found

## New in v 2.0 RC ##

  * Multi Core threading support
  * Lower CPU Usage
  * DivX 5 Support
  * New 8 Preset
  * New Video and Audio Filters

## New in V 2.0  beta : ##
  1. complete rewritten using pygtk [python and GTK+ ](.md)  from realbasic
  1. Multi file conversion
  1. now you can choose your system font for subtitle encoding
  1. subtitle scale [size](.md)
  1. advance feature [custom](custom.md)
  1. new progress window with a screen shot and encoding information
  1. system notification
  1. system try icon menu
  1. a lot of user experience improvement
  1. move log file to user home


## Known issues : ##

  1. subtitle file path and name must not contain a space otherwise it will not be recognize
  1. subtitle font name must be  in one grouped word only  .!


  * E : arial , freeserif,  nazli …...  [good font](this.md)


  * E: droid sans ,  blue highway, DejaVu sans …. [is wrong font and will not be recognize because it contain space  ](this.md)



**This Application is approved by softpedia**

http://linux.softpedia.com/get/Multimedia/Video/DivX-Converter-48666.shtml


### Screenshot : ###

![http://foxoman.files.wordpress.com/2010/01/screenshot_050.png](http://foxoman.files.wordpress.com/2010/01/screenshot_050.png)

![http://foxoman.files.wordpress.com/2010/01/screenshot_051.png](http://foxoman.files.wordpress.com/2010/01/screenshot_051.png)

![http://foxoman.files.wordpress.com/2010/01/screenshot_054.png](http://foxoman.files.wordpress.com/2010/01/screenshot_054.png)

![http://foxoman.files.wordpress.com/2010/01/screenshot_059.png](http://foxoman.files.wordpress.com/2010/01/screenshot_059.png)




### Dependency : ###

  1. Mencoder < Using lavc (divx, x264, xvid) and mp3lame, facc, ac3 >
  1. libfribidi0 < BiDi algorithm implementation for Hebrew and/or Arabic >
  1. ffmpeg2theora < to create the screenshot >
  1. PyGTK < python and GTK+ >
  1. zenity < popup dialog >

Hint :  In usual cases the application will install these component it self but if you encounter any problem check these dependency manually .




## download ##



Debian package


http://foxoman.googlecode.com/files/divxconverter_2.0.1-1_all.deb

redhat package


not yet


source code :

http://foxoman.googlecode.com/files/divxconverter_2.0.1-1_all.tar.gz


PO language template file :

http://foxoman.googlecode.com/files/divxc.po


Upload your translation in the comments