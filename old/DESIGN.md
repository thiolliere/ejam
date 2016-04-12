#User Interface

##init

enter name and MIDI input device

##main

tabulations :
* create session
* [default] browse session
* profil

###create session

* settings
  * name `String`
  * description `String`
  * password `String` (if empty there is not password)
  * style `enum` : jazz, rock, electro, classic, unknown.
  * skill `enum` : beginner, normal, master.
  * soundfont : suggested or upload
* create button : create another window

###browse session

* search settings, filtre
  * search a name
  * search in name + description
  * post/not post  password session
  * filtre style (toggle those you want)
  * filtre skill (toggle those you want)
* refresh button
* list

double click on the session to access.
if session with password -> box appear, write password and then enter.
else enter

###profil

* name
* MIDI input device
