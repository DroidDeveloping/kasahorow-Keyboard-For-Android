kasahorow Keyboard For Android
==============================

kasahorow keyboard for Android. See http://kasahorow.com for more info. 
This project is heavily based on [AnySoftKeyboard](https://github.com/AnySoftKeyboard/AnySoftKeyboard)

Build
====

Clone the repository

`git clone --recursive git://github.com/eyedol/kasahorow-Keyboard-For-Android.git`

The recursive option is there to clone the submodules as well.

After, you should have

```
.
|-- AnySoftKeyboard
|-- AnySoftKeyboard-API
|-- kasahorow-Android-Keyboard
`-- README.md

```

Update the main project and it dependencies. Issue the command below in `kasahorow-Android-Keyboard` as well as in `AnySoftKeyboard-API` and finally in `AnySoftKeyboard`

`android update project -p .`

**Note:** Make sure you've the `android` tool in your `PATH` variable. Makes life easier.

Using ant, in `kasahorow-Android-Keyboard` issue

`ant debug`

If you're an eclipse user, import all the projects into eclipse. Then build `kasahorow-Android-Keyboard` project not any of the library projects. Both `AnySoftKeyboard-API` and `AnySoftKeyboard` are the library projects.