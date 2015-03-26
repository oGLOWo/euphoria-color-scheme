## Euphoria Color Scheme for JetBrains IntelliJ IDEA 12, 13, and 14
This is based off the Monokai scheme from [https://github.com/longcao/monokai-scala-idea](https://github.com/longcao/monokai-scala-idea)

### Screenshots

[![Euphoria Intellij IDEA 12, 13, and 14](https://raw.githubusercontent.com/oGLOWo/euphoria-color-scheme/master/intellij-idea/screenshot-thumb.png)](https://raw.githubusercontent.com/oGLOWo/euphoria-color-scheme/master/intellij-idea/screenshot.png)

### Instructions

1.  Quit IDEA
2.  [Download the Euphoria Color Scheme Here](https://raw.githubusercontent.com/oGLOWo/euphoria-color-scheme/master/intellij-idea/Euphoria.icls)
3.  Install the Color Scheme into your system's color scheme location. See the table below for the proper location on your system. REMEMBER that I'm using version 14 as an example. Don't forget to substitute 12 or 13 if that's what you use.    
4.  This color scheme depends on the Adobe Source Code Pro font that you can [download here](https://github.com/adobe-fonts/source-code-pro/releases/latest) If you don't want to use Source Code Pro, then don't worry about it and just change the font within idea to the font of your choice. Install the font onto your system. Use the OTF fonts first. If anything funny happens, then default to the TTFs. If you don't know how to install the fonts on your system, [visit this page for detailed instructions](https://github.com/adobe-fonts/source-code-pro#font-installation-instructions)
    * ** Special Note for Mac OS X ** and possibly other systems when it comes to Java & Fonts...
    * Installing using something like `FontBook` is not enough. You'll also have to copy the fonts to `$JAVA_HOME/lib/fonts`. Of course you'll want to keep in mind that this may not be the `$JAVA_HOME` that you use for development. For example, Idea12 ran with JDK 6 so I had to copy the fonts to the `jdk6 home/lib/fonts` directory. Now I use 14.1 that can use jdk8 so I copy them to `/Library/Java/JavaVirtualMachines/jdk1.8.0_40.jdk/Contents/Home/lib/fonts` eventhough I use `jdk1.7.x` for my main development \(I do Scala stuff...that's why I'm on 1.7.x\). You may very well have to do some research and trial & error to find the jdk that Idea is using to run. Once you find it, you might need to create the `lib/fonts` directory if it isn't already there.
    * Copy the OTFs to the `jdk_home/lib/fonts` directory. 
5.  Open IDEA.
6.  Go to `Preferences/Settings` and find the section where you can change the theme to Darcula. It is most likely under `Appearance` \-> `UI Options`. Change the Theme to Darcula, and click Apply.
7.  Go to `Preferences/Settings` \-> `Editor` \-> `Colors & Fonts` \-> `Font`, change the Scheme name to Euphoria, and click Apply.
8.  If everything went well, you can now make any customizations such as font size, font weight, selected a different font, etc. 
9.  Let's say you were dead set on having `Source Code Pro` be your font, but to your surprise, you only see one entry or maybe a few. Maybe the regular weight is missing and you only have bold and italic as choices. Well isn't this an absolute fucker? ... Don't worry. I miiiiight be able to get you through this.
10.  Quit IDEA and head over to the jdk's `lib/fonts` directory. Get rid of the OTFs and replace them with the TTF versions.
11.  Start IDEA
12.  Go see if all the `Source Code Pro` font weights and styles are now available. Chances are that they will be and you can now live in peace with your new `Euphoria` color scheme and `Source Code Pro` font. This all happened to me several times so I'm pretty sure this will solve your problem \(should you encounter it\). If it doesn't, you will have to hit Google for answers or send me a message...I might have already figured it out, but haven't updated this README.

### Notes
As of now the focus of this scheme is only on Scala and Java and I don't have time to do much more with it. Feel free to send pull requests with support for other stuff like XML, Groovy, R, Clojure, Brainfuck, JSON, XML, or whatever you want. 

