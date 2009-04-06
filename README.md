# Espresso Theme Library

This is simply a collection of themes for use in MacRabbit's Espresso. The purpose of this repo is to make it easier for Espresso users to download and contribute to existing themes. Until the MacRabbit developers create a better way of installing and developing themes within Espresso, just follow the usage instructions below.


## Usage

Since trying out themes is really tedious and annoying. Open up terminal and do the following.

    $ cd ~/Library/Application\ Support/Espresso/
    $ sudo mv "Themes" "Themes-"
    $ git clone git://github.com/atinypixel/espresso-theme-library.git "Themes"

Final step, just restart Espresso.app and you're all done. In Espresso, go to `Preferences > Colors`. You should see some new or updated themes.

If you want to update the list with new or updated themes just open up terminal and do the following 

    $ cd ~/Library Application\ Support/Espresso/
    $ git pull

Restart Espresso.

### Notes

*Why not submodules?*

Well, I thought of that as well. Unfortunately git unloads files in a directory. So each theme would have it's own directory and Espresso currently doesn't look into subdirectories.

*So I have to maintain my own and this one?*

Personally, it'd be better if everyone could just simply maintain their themes at this repo. It's all in one place and it makes editing other themes a lot less tedious considering otherwise you would have to fork and pull from multiple sources.

**If you would like to be added to this repo, just send me a message and I'll add you.**