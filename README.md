# Using Emacs in Terminal

## Why Emacs ?

Emacs is a very extensible and capable single-threaded editor, written in lisp. It is capable of doing _almost anything_. Joke going around is _Emacs is an OS that lacks a decent editor_. It is not as lightweight as vim, but is capable of much more - like playing _Tetris_. Emacs-ers are capable of doing a full day of work, without ever needing to exit emacs. From viewing mails to setting up to-dos, emacs has community provided packages for all.


## Installing Emacs

Emacs comes with GUI and Terminal version.
GUI version has more features than terminal version, but on servers, we have to use emacs on terminal.

To install Emacs: 

```
sudo apt-get update && apt-get install emacs-nox
```

To start Emacs, write:
```
emacs
```

You should now be greeted with this screen:

![Alt text](emacs.png "Title")



## File operations and navigation

Emacs keybindings are not very beginner friendly. There are starter-packs for emacs which allows one to have normal keybindings, but then that is again a personal preference. Plus, on servers, we are greeted with vanilla-emacs.


### Keys to know

#### Control Key

Emacs makes extensive use of _Ctrl_ key. It is advised to shift _Left Ctrl_ to _Caps Lock_, so as to keep the pinky painless.
It is denoted as **C**.

#### Meta Key

Emacs, by default, takes _Alt_ to be the meta key. It is denoted by **M**.






