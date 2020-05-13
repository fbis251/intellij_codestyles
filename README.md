# FB's Code Style for IntelliJ-based Editors

My preferred Code Style settings for programming in Java with IntelliJ-based editors

### Why?

I like my code to look consistent regardless of when I wrote it and which project I'm working on

### Main Features

* Arranges class members by scope (public first, then protected, package-private, private)
* Sorts class members alphabetically by name
* Chops down long method parameter lines

### Installation

#### Clone the repository

``` bash
mkdir -p ~/src/fbis251
cd ~/src/fbis251
git clone https://github.com/fbis251/intellij_codestyles
```

#### Import the file

1. Navigate to the settings: `File | Settings | Editor | Code Style`
2. Import the file: `Settings Gear (⚙️) | Import Scheme | IntelliJ IDEA code style XML`
3. Navigate to the `FB.xml` file, click it and select OK
4. Click OK on the Import Scheme window

### Usage

From `File | Settings | Editor | Code Style`, select `FB` from the `Scheme` dropdown, then click OK

##### Formatting

1. Open the Java file you want to format
2. Click any line of code to place your caret in the file
3. Press (on Linux) `ctrl + alt + shift + L`
4. Make sure both "Optimize Imports" and "Rearrange Code" are checked and "Whole file is selected"
5. Your code is now formatted!

Going forward, you only need to press `ctrl + alt + L` when you want to format your file
