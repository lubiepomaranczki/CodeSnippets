# CodeSnippets
Custom code snippets for VisualStudio

# How to use? #
1. Download source.
2. Select snippet(s) you want to use.
3. Copy the chosen snippet(s) into ~/Library/VisualStudio/7.0/Snippets/ (the folder is hidden by default, so either open in from terminal or make hidden files visible (see at the end of this readme how to).
4. Use it ;-)

# NOTE 
In my case snippets are in folder 7.0 but it might change during 

Snippets in:
# Visual for Mac #
In here you will find my snippets for Visual Studio for Mac. The name of the snippet is the shortcut in VS for Mac.

## 1. mprop ##
Creates public MVVM property with Get, Set, and OnPropertyChanged(nameof(Test))

## 2. mcmd ##
Creates public command property with a associated private command

## 3. mreg ##
Generates regions in class for: fields, properties, constructor(s), methods

## 4. mview ##
Creates empty template for a MVVM view. With regions, overrides and injected viewmodel.

## 5. mvmm ##
Creates public property ViewModel with get method which returns BindingContext as ViewModel

# GENERAL #

## 1. REGIONS ##
Shortcut: regions

Generates regions in class for: fields, properties, constructor(s), methods

# MVVM #

## 1. MVVM VIEW ##
Shorcut: mview

Generates code for view in MVVM with constructor and propertie for ViewModel. Also adds regions


### Show hidden files in Finder
1. Open terminal,
2. Type `defaults write com.apple.finder AppleShowAllFiles YES` and press Enter
3. Make sure you don't have any thing important open in Finder - we need to restart it.
4. Type `sudo killall Finder` - Boom the Finders got closed!
5. Enjoy your hidden files visible
