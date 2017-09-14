# Mixxx skin: Dark Metal

![mixxx_dark_metal_thumb](https://cloud.githubusercontent.com/assets/5511928/22786461/937bac60-eed0-11e6-866a-d2e5b9fa17f6.jpg)

**DARK METAL SKIN FEATURES:**

1) 100% Scalable Vector Graphics (SVG) - 100% Quality lossless graphics - Not even one bitmat anywhere.
2) Fully resizable - Small screen users can use it too - All elements must fit nicely in all resolutions. Please note that If your resolution is too small, some racks (rows) may overlap, but even so you still can disable their visibility (there are lots of buttons, in the top bar, for that. These buttons are always visible, no matter what, even you "enable" everything). Ready from 1024x550, to... infinity and beyound.
3) Mixxx features - Contains the lattest Mixxx features - But... I´m sure that not all tasks arent done, so I´m always sharping the graphics, correcting issues, adding forgotten and/or new stuff, etc...
4) Unique features - Contains unique and original features (I´ll try to add features not available anywhere else, but they must be functional too, of course) Like the analog VUs, the digital font, a grey only color scheme (A tribute to 1927´s Metropolis film), strobe lights, etc, etc... Our imagination versus the code will be the limit...

=================================================================================

**How-Tos...**

**HOW-TO:** Install Dark Metak Skin?...
1) Remove any older version of "DarkMetal". *(Just delete the "DarkMetal" folder... IF you already have one)*
2) Download and unzip the "DarkMetal.zip" archive. *(~1.5Mb file size)*
3) Move the new folder (with all contents), to your Mixxx skins folder. *(An path example in Windows OS: C:\Program Files\Mixxx\skins\DarkMetal)*
4) Double click in the included "digital.otf" to install that font.
5) Start your Mixxx, then go to "Options" --> "Preferences" --> "Interface" --> "Skin" --> Select "DarkMetal" option.
6) Done!...

**HOW-TO:** Change between the three available type of "strob lights"?... (squared/rounded/line)
1) Open the "skin.xml" search and replace the variable "strobtype"´s value by "1", "2" or "3".
2) Save the file. Reload the skin... Done!...

**HOW-TO:** Change between the three available spinning "discs"?... (bobine/cd/vinyl)
1) Open the "skin.xml" search and replace the variable "spinnytype"´s value by "1", "2" or "3".
2) Save the file. Reload the skin... Done!...

**HOW-TO:** Select one from the many available color schemes?...
1) Start your Mixxx, then go to "Options" > "Preferences" > "Interface" > "Color scheme" > select a color from that list.
2) Done!...

**HOW-TO:** Create my own custom color scheme?...
1) Open the "skin.xml" file.
2) Create a new <Scheme> group, play with <HConst> and <SConst> values (see the existent ones there as examples), save that file and reload the skin to test it (this is done by selecting the "DarkMetal" skin again, from that dropdown menu). And... If the result is great, don´t forget to share it with us!!
3) Done!...

**HOW-TO:** Create and display my own logo?...
1) Open any "logo_x.svg" file. These files are located at the "graphics-logos" folder. (You may use INKSCAPE to open/edit or create a new logo file)
2) Draw your own logo, or just type your texts there. (Texts must be converted to paths, before save file)
3) Open the "skin.xml" search and replace the variable "mylogo"´s value by "1", "2", "3", etc... (Set the number to display the logo file that should be displayed at this moment)
4) Save all the files. Reload the skin... Done!...

---------------------------------------------------------------------------------

**The "making of" Dark Metal skin:**

**TOOLS:**
1) Notepad++ (My preferred to edit XML files): https://notepad-plus-plus.org ...OR... The "modernish" Atom: https://atom.io
2) INKSCAPE (To draw the vectorial graphics): https://inkscape.org
3) SVG Explorer Extension (Very handy and useful since it generates SVG thumbnails in the Windows´s explorer): https://svgextension.codeplex.com/releases/view/118790 ...OR... For GNU/Linux users, one from these (choose only the ones with SVG support, of course): http://www.tuxarena.com/2011/02/top-5-i ... ntukubuntu

**TIPS:**
1) The included SVG files in this skin, not only are the screen displayed "images", but they are the EDITABLE/WORKING files too, so they can be opened and customized by anyone else too. You just need to have INKSCAPE or similar.
2) Avoid Corel Draw - Very powerfull and great software, but it adds extra proprietary metadata in the SVG files, what results in huge file sizes and it converts shadows into bitmaps. Besides all that, most of those files just can´t be parsed with Mixxx, or any other "standard" opensource SVG parser.
3) Always export SVG files (from INKSCAPE) with all texts converted to paths!
4) Preparing graphics to handle all the possible color <Schemes> correctly (When system is processing colors, to generate a new color scheme, colors may blur borders (eg: Very visible at the buttons), this happens because that colors are overriding theirs (normally defined by 1px strokes) own limits, what makes the visuals very ugly and incorrect). To avoid this: A) Degradee the colors to 100% black (or white) just before it reaches your graphic maximum width or height, just 1px before, will be enought. B) Void set <VConst> values. 0 (zero) should always be "perfect".
5) Want to broadcast (for tests or to create your own radio)? Just go here: http://www.listen2myradio.com (Its the one that I use, fast to create an account, HQ audio stream, decent radio urls, allows 5000 listeners on the free plan, decent backoffice, decent in overall aspects). I´ve tried many many others... Just wasting my time!... Don´t waste yours... (There could be much better audio streaming servers than this one, of course. But I havent found any until the moment, and I´m completly happy with this one... at least, until now... )

---------------------------------------------------------------------------------

LICENCE: Creative Commons - Attribution 3.0 Unported - https://creativecommons.org/licenses/by/3.0

---------------------------------------------------------------------------------

Tutorial Video: https://www.youtube.com/watch?v=-FIc3iiHDeU&index=40&list=PLnhzSMPecj1HXo5IGrNFYiGyy6fHZYPTL

DARK METAL skin at MIXXX forums: http://www.mixxx.org/forums/viewtopic.php?t=6052
	
---------------------------------------------------------------------------------

- This project at GITHUB: https://github.com/jorgerosa/Mixxx-DarkMetal-Skin
- This project at SOURCEFORGE.NET: https://sourceforge.net/u/jorgerosa/profile
- Developer: Jorge Rosa *(Portugal - With love to ASCR)*
- Email: jorge.bigarte@gmail.com
- Portfolio: http://sites.google.com/site/jorgerosaportfolio *(Many more stuff there...)*

---------------------------------------------------------------------------------
