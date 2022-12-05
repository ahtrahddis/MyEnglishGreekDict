# My English to Greek Dictionary - a free English to Greek dictionary for Kindle

This Kindle dictionary is the result of a **stardict** to **mobi** conversion of an old **English to Greek** dictionary found on [Mobileread](https://www.mobileread.com/forums/showthread.php?t=288657).

Most probably, this used to be a Babylon community dictionary of the early 00's.


## Original author and information

	version	2.4.2
	wordcount	48527
	synwordcount	45198
	idxfilesize	896658
	author	Giannacoulis George


### Dictionary description in Greek 

>Αγγλοελληνικό λεξικό με πάνω από 48000 λέξεις, ειδικούς όρους (από διάφορα επιστημονικά πεδία), ιδιωματισμούς και παροιμίες. Το λεξικό εμπλουτίζεται διαρκώς, συμπληρώνονται νέοι όροι και προστίθενται ερμηνείες ενώ  ταυτόχρονα γίνονται, όπου κρίνονται  απαραίτητες,  σχετικές διορθώσεις. Επιπροσθέτως τελευταία γίνεται προσπάθεια παράθεσης παραδειγμάτων χρήσης των λέξεων.

### About the author

Unfortunately I can't find a lot about **George Giannacoiulis**, apart from an archived version of his website:

 [http://users.sch.gr/gyiann](https://web.archive.org/web/20080516145509/http://users.sch.gr/gyiann/)

## License

Until today it has been impossible to find any information with regards to the license of the original dictionary.

This was most probably an unlicensed work.

However, this fork is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).


## Creation how-to

For the creation of this dictionary, I used the following procedure:


1. I converted the **stardict** dictionary to **tabfile** format (txt), using [pyglossary](https://aur.archlinux.org/packages/pyglossary)
2. I created the **opf** and **html** files with **tab2opf.exe** (using -utf option) from [1manfactory.com](https://1manfactory.com/create-your-own-kindle-dictionary-for-every-language-for-free/). I runned this tool under Linux, using Wine.
3. I edited the **opf** file using a text editor
4. I created the **mobi** file with [kindlegen for Linux](https://aur.archlinux.org/packages/kindlegen).


## Download (V 1.00 - 2022-12-05)