# #100DaysOfCode Log - Round 1 - Brandon Le

The log of my #100DaysOfCode challenge. Started on July 7th, 2021.

## Log

### R1D1
<!-- Started a Weather App. Worked on the draft layout of the app, struggled with OpenWeather API http://www.example.com -->

Started a simple gesture app [here](https://github.com/thesamuraiwho/simple-gesture-show). That is based on my project on another account [here](https://github.com/greenunknown/simple-gesture-slideshow) that uses PySimpleGUI. Mostly working on Pexels API. I had issues with authorization and accessing various resources but now can search and access public collections. However, original size images sometimes display black bars.

Also, I followed [Miguel Grinberg's tutorial](https://blog.miguelgrinberg.com/post/how-to-create-a-react--flask-project) to create a react flask project.

### R1D2

Started a GUI app to download Pexels Collections [here](https://github.com/thesamuraiwho/pexels-collection-downloader) to get some experience to build up to the simple gesture app. Mostly was dealing with issues with PySimpleGUI and re-learning how to setup the layout and tried creating a settings file.

### R1D3

Re-designing app to be two windows (one for setup, such as the API, and one to select collections and download). Having a bit of issues trying to get some of the code to play nicely so didn't get much working. Had a huge problem with accessing the repo with SSH keys and finally gave up and set my old account as a collaborator. ;)

### R1D4

Re-design the app again now with two user paths: initial setup and already setup. Working on pysimplegui to get it to start with a window to prompt for the api key when the the settings.json only has a blank key. Having issues with this, collections not being all requested, interaction between clicking a selection in the listbox to show details in a text element.

### R1D5

Missed so added a day 101.

### R1D6

Adding functionality to capture up to 80 collections in one go, but currently don't handle 80+ collections. Adding description of collection upon selection in listbox. Currently this display is not efficient since a list comprehension is created for each field.

### R1D7

Adding functionality to get every collection instead of up to 80. Working on getting downloading pictures and videos next. Major struggle was determining the write way to approach combining the multiple json requests that may be required.

### R1D8

Refactoring code and simplifying work. Adding downloading pictures and videos.

### R1D9

Working on getting image preview. Issue with handling media api and figuring out a good way to display preview selection of a

### R1D10

Spent most of the time trying to fix my get_json() function since it would not combine dictionaries together correctly. Still trying to fix it.

### R1D101
