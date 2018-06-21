# Displays App
This is a node app that resides on a Raspberry Pi
## Architecture
The Architecture for this app is a skeleton Node application that calls an API with credentials.
The API returns the display template to use and the images used for the display.
The app then displays the template and the ad images in the sequence set up in the template.


# Issues
I am having major issue with the installation of the app on the Raspberry PI, as it is an ARM architecture, which require a special version of Node.
This special version does not recognize ES6 script syntax, so any module written in the newer syntax causes errors.
I am working to resolve this issue.

If I cannot find a solution, I may be looking into writing this in Python and TkInter instead.
