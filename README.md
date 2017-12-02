# Responsive Google Copy

#### A copy of the "Think with Google" webpage using responsive CSS, December 1, 2017

#### By **Luke Bertram**

## Description

This is an attempt to recreate the "Think with Google" webpage using responsive CSS styling. It was started using the Materialize CSS framework. It was finished with a terrible struggle to work within the confines of that framework.

## Setup/Installation Requirements

For greatest ease of use, simply visit [this website](http://lukebertram.github.io/copy-google) in your web browser of choice. However, if you're feeling frisky, you can also use the following steps to clone the project from [GitHub](http://github.com) and run it locally on your own computer:

 * Visit the github page for [this project](http://github.com/lukebertram/copy-google)
 * Click the "Clone or Download" button and copy the address found there. Alternatively, just copy this address to your clipboard: https://github.com/lukebertram/copy-google.git
 * Access your system's command line interface (_ie Terminal, for MacOS Users_) and navigate to your home directory by entering the following magical spell into your command line (note: do not enter the '$' character):
 >$cd ~

 * Next, cast the following, more advanced spell:  
 >$git clone https://github.com/lukebertram/copy-google.git

 * Finally, open the project in your system's default web browser with the following final incantation:
 >$open copy-google/index.html


## Known Bugs

Everything is at least slightly wrong. It pains me.

The nav bar is all messed up, and I spent way too much time messing with it before I realized it was not part of the assignment. So I left what functionality was already there with the intent to come back to it later if I had enough time. I did not have enough time. I need to add the logo and override Materialize's styling to prevent the mobile menu from being absolutely positioned over the logo placeholder. Also, I need to replace the placeholder with the actual logo.

The margins of elements in the "Latest Trends and Stories" section are all messed up. I have so far not been able to reconcile my desired margins for these elements with the behavior of Materialize's grid system.

## Support and contact details

Flag me down in class, or send me a tweetbook on facestagram if you have any troubles.

## Framework Used

The decision was made early on to utilize Google's "Materialize" framework. That decision was later regretted, as I found myself spending more time trying to work my layout ideas into the framework or struggling against its default behaviors than I would have spent if I had styled the whole dang mess on my own.

### License

MIT License

Copyright (c) 2017 **Luke Bertram**
