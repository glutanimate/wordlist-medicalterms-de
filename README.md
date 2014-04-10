## README for wordlist-medicalterms-de


###Overview

    Description:        dictionary of German medical terms
    Terms:              6532
    Author:             Glutanimate (https://github.com/Glutanimate)
    Original Author:    Tobias Quathamer (https://launchpad.net/~toddy)
    Source:             medicalterms (20110608-1)
    License:            GNU GPL v3 (see LICENSE.txt for more information)


###Description

This is a simple list of German medical terms formatted as a UTF8-encoded text file. It is based on the medicalterms project by Tobias Quathamer and was designed to work with Android dictionary managers.


###Usage

**Android**

Copy `wordlist.txt` to the root directory of your Android phone. Then install the excellent [User Dictionary Manager](https://play.google.com/store/apps/details?id=com.usr.dict.mgr) by Adrian Vintu and use it to import the terms to your user dictionary. More information may be found [here](http://udm.adrianvintu.com/). Note: Because of the size of the wordlist importing might take a while.

**LibreOffice**

*Automatic installation*

If you are using Linux your distribution might be shipping with a ready-made package of this dictionary (e.g. `hunspell-med-de` on Ubuntu). Unfortunately add-on dictionaries don't appear to work properly in recent version of LibreOffice (1). I advise to try the package in your distribution's repository out before deciding to manually install my wordlist. 

*Manual installation*

Follow the instructions provided in [this Q&A](http://ask.libreoffice.org/en/question/11170/create-basic-english-dictionary/?answer=11187#post-id-11187) to create a new custom dictionary. Make sure to name it in a recongizable fashion (e.g. medicalterms.de) and activate it in the menu. 

[Find out where your LO user profile is located](https://wiki.documentfoundation.org/UserProfile#User_profile_location). Then proceed to navigate to `<LO user profile directory>\3\user\wordbook` and find your dictionary (e.g. medicalterms-de.dic). Open it in a text editor of your choice (e.g. Gedit on Ubuntu; Notepad++ on Windows, NOT Notepad!). Copy and paste the full contents of `wordlist.txt` below the dashed line (`---`). Save the file while making sure it remains UTF-8 encoded and restart LibreOffice.

**Word**

Rename `wordlist.txt` to `medicalterms-de.dic` and follow the instructions provided [here](http://support.microsoft.com/kb/322198).


###Waranty

This software comes with no warranty of any kind. Some misspelled words might be included. Please make sure to submit a [bug report with the original project](https://bugs.launchpad.net/medicalterms) if you find any mistakes.

###Sources

(1): https://bugs.launchpad.net/ubuntu/+source/language-support-extra-de/+bug/363619, https://bugs.launchpad.net/ubuntu/+source/openoffice.org/+bug/329968 and https://bugs.launchpad.net/medicalterms/+bug/401423
