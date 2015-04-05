# Package Converter #

### _Package Converter 3 is out [4/july/2009 ](.md)_ ###

## _Frontend for Alien_ ##

**Description :**  Package Converter is an alien frontend .  Alien is a program that converts between Red Hat rpm, Debian deb, Stampede slp, Slackware tgz, and Solaris pkg file formats. If you want to use a package from another linux distribution than the one you have installed on your system, you can use alien to convert it to your preferred package format and install it. It also supports LSB packages.

**With this application you will be able to convert between [deb , rpm ,tgz , lsb, slp, pkg](.md) , with all alien options supported .**


Package Converter is  written using _Realbasic_.


**Softpedia Download and review page**

[![](http://www.softpedia.com/images/softpedia_download_small.gif)](http://linux.softpedia.com/get/System/Software-Distribution/Package-Converter-46633.shtml)

### Dependency : ###
  * alien
  * fakeroot

### Standard feature : ###
  * convert between deb , rpm ,tgz , lsb, slp, pkg
  * support alien options
  * easy GUI

### New in Release 3.0.0.2 : ###

  * New GUI .
  * More Option support ( Now it support all  alien options ) .
  * tips and captions to help you to understand the options .

### Screenshot : ###

![http://img36.imageshack.us/img36/9739/screenshot017k.png](http://img36.imageshack.us/img36/9739/screenshot017k.png)

**How to use**

**Download** : [RPM](http://foxoman.googlecode.com/files/package-converter-3.0.0.2-2.noarch.rpm) | [DEB](http://foxoman.googlecode.com/files/package-converter_3.0.0.2-2_all.deb)

To lunch the application go to
```
Applications --- system tools ---- package converter
```


Simply select your package file you want to convert , and select the folder you want to save the result file to. Then , select package type you want to convert to .

_ie : you want to convert opera.deb file to rpm in home folder_

First , select opera.deb . and then select home folder to save the result file.

Then , select rpm in package type list , and click convert !

### Video Tutorial ###

http://www.youtube.com/watch?v=oV2D1_J8SE4&feature=response_watch Thanks to gotbletu

## Known-bugs : ##

  * File path and folder path should not contain any spaces otherwise the conversion will fail .

Example : /home/romance/untitled folder/opera.deb

  * Package Converter 3.0.0.2 message window won't scroll [issue-2](http://code.google.com/p/foxoman/issues/detail?id=2)

You can copy the output MSG by clicking inside the output window then click

> CTRL + A + C


Wait a few seconds before clicking on C :)


  * If want to use description option use double quote IE : "Package converter is blah blah ..." otherwise the conversion will fault .


**Bug Report**

Feel Free to report any bugs or suggestion in [issues](http://code.google.com/p/foxoman/issues/list) page

## ubuntu forums ##

http://ubuntuforums.org/showthread.php?p=7700487