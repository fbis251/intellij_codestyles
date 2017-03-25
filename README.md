# FB's Code Style for IntelliJ-based Editors

My preferred Code Style settings for programming in Java with IntelliJ-based editors

### Why?

I like my code to look consistent regardless of when I wrote it and which project I'm working on

### Main Features

* Arranges class members by scope (public first, then protected, package-private, private)
* Sorts class members alphabetically by name
* Chops down long method parameter lines

### Installation (Linux)

    # Clone the repository
    mkdir -p ~/src/fbis251
    cd ~/src/fbis251
    git clone https://github.com/fbis251/intellij_codestyles

##### For Android Studio 2.x

    # Make sure you're creating this in the appropriate folder for the current version of Android Studio
    mkdir -p ~/.AndroidStudio2.x/config/codestyles
    cd ~/.AndroidStudio2.x/config/codestyles
    ln -s ~/src/fbis251/intellij_codestyles/FB\ Android.xml

### Usage

After installing, the Code Style settings are now available in your IntelliJ-based editor

##### Initial Setup

1. Open your editor
2. Navigate to Settings > Editor > Code Style
3. Under the Scheme dropdown, select "FB Android"
4. Click Apply

##### Formatting

1. Open the class you want to format
2. Click a line of code for that class
3. Press (on Linux) ctrl + alt + shift + L
4. Make sure both "Optimize Imports" and "Rearrange Code" are checked and "Whole file is selected"
5. Your code is now formatted!
