quiver2jekyll
=============

A utility to convert a Quiver note to a markdown post for Jekyll. 

[Jekyll](http://jekyllrb.com/) is a great platform for creating blogs. However it can be a bit tedious working in markdown directly from a text editor, particularly for technical posts with lots of code. 

[Quiver](http://happenapps.com/#quiver) is a great notebook app built for programmers. Code and text can be freely mixed. 

quiver2jekyll enables blog writers to use Quiver to write their blog posts and export the final result into markdown for use in Jekyll. 

## Features

- Front matter generation: title and tags are extracted from the Quiver note
- Code Highlighting: Exported code cells apply code highlighting to your post

## Installation

- [Download the script](https://raw.githubusercontent.com/bradley-curran/quiver2jekyll/master/quiver2jekyll)
- Put it on your path
- `chmod u+x quiver2jekyll`

## Usage

- Select the note you want to export in Quiver
- In the toolbar, select File > Export Note...
- Save the note to your Desktop, e.g: latestblogpost.qvnote
- Open Terminal
- `cd ~/Desktop`
- `quiver2jekyll latestblogpost.qvnote/`
- Copy the generated file into your `_posts` folder

## Feature Requests and Issues

Feel free to [add an issue or feature request](https://github.com/bradley-curran/quiver2jekyll/issues). Pull requests are welcome as well! 
