# CSS Level 3—Textmate Bundle

By Matthew Sanders—matt@optionshft.com

<img src="http://matthewnsara.com/images/css3-textmate-bundle-preview.png" alt="CSS3 TextMate Bundle - Preview" />

## Installation

The best way to install this bundle is via command line. Simply copy and paste each line into a terminal window.

### Install via Git:

		mkdir -p ~/Library/Application\ Support/TextMate/Bundles
		cd ~/Library/Application\ Support/TextMate/Bundles
		git clone git@github.com:mattsanders/CSS3-TextMate-Bundle.git "CSS3.tmbundle"
		osascript -e 'tell app "TextMate" to reload bundles'

Source can be viewed or forked via GitHub: [http://github.com/mattsanders/CSS3-TextMate-Bundle/tree/master](http://github.com/mattsanders/CSS3-TextMate-Bundle/tree/master)

### Install without Git:

		mkdir -p ~/Library/Application\ Support/TextMate/Bundles
		cd ~/Library/Application\ Support/TextMate/Bundles
		wget http://github.com/mattsanders/CSS3-TextMate-Bundle/tarball/master
		tar zxf mattsanders-CSS3-TextMate-Bundle*.tar.gz
		rm mattsanders-CSS3-TextMate-Bundle*.tar.gz
		mv mattsanders-CSS3-TextMate-Bundle* CSS3.tmbundle
		osascript -e 'tell app "TextMate" to reload bundles'

## Basic Commands

These are the basic commands you may use for tab-completion with your stylesheets.

* radius ( border-radius: )
* boxshadow
* gradient
* nth
* columns 
* textstroke 
* taphighlight 
* textshadow 
* transition 
* userfocus 
* usermodify 
* userselect 
* rgba 

### CSS Template

Select File > New From Template > CSS3 > CSS Template

## Author

Matthew Sanders, matt@optionshft.com

Website [http://optionshft.com](http://optionshft.com) 
Twitter [http://twitter.com/mattsanders](http://twitter.com/mattsanders)
Dribbble [http://dribbble.com/matthew](http://dribbble.com/matthew)



License
=======

<a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/3.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Dataset" property="dct:title" rel="dct:type">CSS3 TextMate Bundle</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="http://optionshft.com" property="cc:attributionName" rel="cc:attributionURL">Matthew Sanders</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/3.0/">Creative Commons Attribution-ShareAlike 3.0 Unported License</a>.