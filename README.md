# SublimeText Earthly Syntax README

Syntax highlighting for [Earthly](https://earthly.dev) Earthfiles for Sublime Text.

For an introduction of Earthly see the [Earthly GitHub repository](https://github.com/earthly/earthly) or the [Earthly documentation](https://docs.earthly.dev).

## Installation Notes

### For Sublime 3

* From Sublime -> `Preferences` -> `Browse Packages` -> This will open a directory
* Copy the `Earthfile.tmLanguage` and `Earthfile.tmPreferences` inside this directory and the syntax will be added to Sublime
* After this, new Earthfiles that you open will have the syntax highlighted, and for the already opened earthfiles, either reopen it, or restart sublime, or select `View` -> `Syntax` -> `Earthfile`

### For Sublime 2

* From Sublime -> `Preferences` -> `Browse Packages`
* It will open a directory similar to `<Installation Directory>\Data\Packages`
* It will have a lot of dircetories with language names such as `C++`, `Java`, `Python` and many more.  We need to create a folder called `Earthfile` and copy the `Earthfile.tmLanguage` and `Earthfile.tmPreferences` inside the newly created directory
* After this, new Earthfiles that you open will have the syntax highlighted, and for the already opened earthfiles, either reopen it, or restart sublime, or select `View` -> `Syntax` -> `Earthfile`

## Screenshot

![sublime syntax highlighting screenshot](Screenshot.png)


## Release Notes

### 0.0.1

Initial release of earthfile-syntax-highlighting with readme and screenshot
