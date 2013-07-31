euphoria-color-scheme
=====================

Euphoria color scheme collection for various editors and IDEs. 

## Intellij IDEA 12
This is based off the Monokai scheme from [https://github.com/longcao/monokai-scala-idea](https://github.com/longcao/monokai-scala-idea)

### Screenshots

[![Euphoria Intellij IDEA 12](https://raw.github.com/oGLOWo/euphoria-color-scheme/master/intellij-idea12/screenshot-thumb.png)](https://raw.github.com/oGLOWo/euphoria-color-scheme/master/intellij-idea12/screenshot.png)

### Instructions

1. Quit IDEA
2. [Download the Euphoria Color Scheme Here](https://raw.github.com/oGLOWo/euphoria-color-scheme/master/intellij-idea12/Euphoria.icls)
2. Install the Color Scheme into your system's color scheme location. For me, on Mac OS X, it's `~/Library/Preferences/IntelliJIdea12/colors`
3. This color scheme depends on the Adobe Source Code Pro font that you can [download here](http://sourceforge.net/projects/sourcecodepro.adobe/files/SourceCodePro_FontsOnly-1.017.zip/download) If you don't want to use Source Code Pro, then don't worry about it and just change the font within idea to the font of your choice. Install the font onto your system. For example, on Mac OS X, use `FontBook` to install it. 
    * ** Special Note for Mac OS X ** and possibly other systems on Java/fonts
    * Installing using something like `FontBook` is not enough. You'll also have to perform the following step:
    * Copy the TTFs (I didn't have much luck with the OTFs, but you can try) to `/Library/Java/Home/lib/fonts/` . If that location doesn't exist on your Mac, then just find the location where java 6 is installed on your system. Intellij IDEA uses Java 6 to run so that's why they have to be in the Java 6 `/lib/fonts` location. If you run IDEA with Java 7 or when they put out a version that runs with Java 7, just throw the fonts into 7's lib/fonts directory.
4. Open IDEA.
5. Go to Preferences -> IDE Settings -> Appearance -> UI Options, change the Theme to Darcula, and click Apply.
6. Go to Preferences -> IDE Settings -> Colors & Fonts, change the Scheme name to Euphoria, and click Apply.
7. Make any of your own customizations such as font size and line spacing if desired

### Notes
As of now the focus of this theme is only on Scala and Java, but feel free to send pull requests with support for other stuff like XML, Groovy, etc.




