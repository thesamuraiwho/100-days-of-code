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

### R1D11

Missed day so added d102

### R1D12

Determined the issue with json collections media merging due to conflicting names for keys causing values to be replaced rather than combined. Solution uses the tag 'media' rather than the whole thing. Thus, instead of working on dictionaries, I'm working with lists. Did hit rate limit for api so will need to check for that in the future and reduce requests.

### R1D13

Missed day so added d103

### R1D14

Adding work on downloading photos and videos and file browser for download location. Still working on cleaning up the layout of the window layout and handling edge cases.

### R1D15

Missed day so added 104

### R1D16

Adding home path setting, photo quality selection, and GUI layout with columns. Cleaning up code.

### R1D17

Adding output box to inform user. Outputs messages for selecting a collection, changing photo download quality, and download info. May add options for controlling downloading photos and videos, photos only, and videos only.

### R1D18

Adding media options to download. Resizing the layout. Sorting list box options for collections. Refactoring code. Still trying to figure out edge cases and how to deal with invalid api and invalid home directory.

### R1D19

Optimizing the layout of the app to be more space efficient. Adding url tooltip links for my github and pexels.com. Working on getting api key validation and hourly rate check but having a lot of issues trying to handle the issue and figuring out where to handle it. Also, having a bug with monthly rate limits somewhere.

### R1D20

Adding checks for API and home directory and appropriate indications for invalid input for initial setup. Struggling with cleaning up the code and handling events for changing settings later on. Still having issues with the rate limit, quota reset time, and hourly use.

### R1D21

Refactoring codebase to reduce complexity and verbosity. Fixed change settings option. Need to handle excpetions and clean up code further but most of the app is working. Still have an issue with api rate limit and quota time.

### R1D22

Removing the rate limit and quota functionality because of limitations in time. Adding handling of case where valid settings but issue with communication with api itself. Planning on wrapping up the app soon hopefully just to get on to the next thing.

### R1D23

Working on simple gesture app now while getting help to qa and release the pexels downloader app. Just some dusting off of old code and setting up basic settings to make app similar to adorkastock and line of action.

### R1D24

Missed day so adding d105.

### R1D25

Spent time creating a release candidate [here](https://github.com/thesamuraiwho/pexels-collection-downloader/releases/tag/v1.0.0-rc1). Tried using igraph module but had many issues getting it to work from setup. Integrating settings for the gesture app.

### R1D26  

Working on UI for gesture app. Trying to change app to be single page.

### R1D27

Missed day so adding d106.

### R1D28

Working on gesture app. Creating browsing and app initialization in one page. Working on three modes for the app.

### R1D29

Adding mode cycling. After successfully opening a folder of images the constant mode controls are shown. These controls can be changed depending on the mode the user want to choose.

### R1D30

Adding stopwatch functionality. Having issues with the reset after time hits zero because the next second is cut short.

### R1D31

Adding nexttimeout selection for constant mode. Refactoring the buttons for uniform looks.

### R1D32

Missed day so adding d107.

### R1D33

Updating pexels downloader for rc 2. Adding class mode checks on gesture app.

### R1D34

Adding more checks for gesture app to change between the three sub modes.

### R1D35

Separating file browsing and controls. Refactoring and redesigning code.

### R1D36

Adding work on getting info on poses for class mode. Having issues with UI time reset not reacting to switching modes correctly yet and issues with pose switching in class mode.

### R1D101

### R1D102

### R1D103

### R1D104

### R1D105

### R1D106

### R1D107
