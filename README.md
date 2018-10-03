# Sprout Demo

A Craft 3 installation with the Sprout Plugins in place.

## Using barrelstrength/sprout-demo

This project package works exactly the way Pixel & Tonic's [craftcms/craft](https://github.com/craftcms/craft) package works; you create a new project by first creating & installing the project:

    composer create-project barrelstrength/sprout-demo PATH

Make sure that `PATH` is the path to your project, including the name you want for the project, e.g.:

    composer create-project barrelstrength/sprout-demo ./sprout-demo

Then `cd` to your new project directory, and run Craft's `setup` console command to create your `.env` environments and optionally install:

    cd PATH
    ~/path/to/project/craft setup

Finally, run the `sprout-demo-setup` command to configure Sprout & Craft 3

    php ./sprout-demo-setup

That's it, enjoy!
