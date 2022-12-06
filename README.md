# MyEnglishGreekDict - a free English to Greek dictionary for Kindle

This Kindle dictionary is the result of a **StarDict** to **mobi** conversion of an old **English to Greek** dictionary found on [Mobileread](https://www.mobileread.com/forums/showthread.php?t=288657).

Most probably, this used to be a Babylon community dictionary of the early 00's.


## Original author and information

	version	2.4.2
	wordcount	48527
	synwordcount	45198
	idxfilesize	896658
	author 	Giannacoulis George


### Dictionary description in Greek 

>Αγγλοελληνικό λεξικό με πάνω από 48000 λέξεις, ειδικούς όρους (από διάφορα επιστημονικά πεδία), ιδιωματισμούς και παροιμίες. Το λεξικό εμπλουτίζεται διαρκώς, συμπληρώνονται νέοι όροι και προστίθενται ερμηνείες ενώ  ταυτόχρονα γίνονται, όπου κρίνονται  απαραίτητες,  σχετικές διορθώσεις. Επιπροσθέτως τελευταία γίνεται προσπάθεια παράθεσης παραδειγμάτων χρήσης των λέξεων.

### About the author

Unfortunately I can't find a lot about **George Giannacoulis** (who I thank A LOT for creating this dictionary!), apart from an archived version of his website:

 [http://users.sch.gr/gyiann](https://web.archive.org/web/20080516145509/http://users.sch.gr/gyiann/)

## License

Until today it has been impossible to find any information with regards to the license of the original work and I assume that it was most probably unlicensed.

However, this fork is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).


## Creation how-to

For the creation of this dictionary, I used the following procedure:


1. I converted the **StarDict** dictionary to **tabfile** format (txt), using [pyglossary](https://aur.archlinux.org/packages/pyglossary).
2. I created the **opf** and **html** files with **tab2opf.exe** (using -utf option) from [1manfactory.com](https://1manfactory.com/create-your-own-kindle-dictionary-for-every-language-for-free/). I ran this tool under Linux, using Wine.
3. I edited the **opf** and **html** files using a text editor.
4. I created the **mobi** file with [kindlegen for Linux](https://aur.archlinux.org/packages/kindlegen).


## Download (V 1.1 - 2022-12-05)

- [MyEnglishGreekDict_11.mobi](https://github.com/ahtrahddis/MyEnglishGreekDict/raw/main/MyEnglishGreekDict_11.mobi)


## Installation instructions

1. Connect your Kindle with your Laptop/PC.
2. Copy MyEnglishGreekDict.mobi to /documents/dictionaries folder.
3. Unmount, disconnect and restart your Kindle.
4. Don't use it as your default dictionary - having an English to English as your default one, ensures that your Kindle will use it as a fallback solution. Instead, choose *"My English to Greek Dictionary"* from within the book you are currently reading. 

**Notes:** 

- This file has been tested with Paperwhite 7th and 11th generation, running the latest available firmware.
- I suggest you to add [freeeneldict](https://freeeneldict.wordpress.com/) too and use it along with this one!

## Changelog
- V 1.0 - Initial commit
- V 1.1 - various fixes (typos) & enhancements in html formatting
