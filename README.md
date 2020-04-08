# Fake linux Terminal web client
Based on  luisbraganca/fake-terminal-website , I juxt make it draggable 
It can be used for educational purposes or as a bio or resume and of course FUN!!!

Functionalities

    Fully generic website easy to customize according to the user's needs
    TAB autocompletion support
    A few linux-like possible commands
    Typewriter effect when showing a command result
    Possible to skip the typewriter effect by doubleclicking anywhere
    Sidenav with all the files to make it easy for people with no know-how to navigate through your website . but (display:none)
    Since the website is generic enough, you're able to create a language-checker function and associate different texts according to the user's browser language (my website version has support for both portuguese and english languages).
    Using Arrow keys for command history
Future (TODO) functionalities

    Ask for a password when using sudo command
    email or similar command that allows the visitor to send an email directly to the website owner
    make website responsive 
    scalable Terminal size
    
    
 Configuring the website

Before you deploy the website, consider changing the following:

    Go to js/main.js and replace all the text on both singleton vars:
        configs: Contains all the text used on the website plus a few configurations.
        files: All the fake files used on the website. These files are also used to be listed on the sidenav. Also please notice if a file content is a raw URL, when clicked/concatenated it will be opened on a new tab.
    The page title on the index.html file.
    The website color on the css/main.css file.
    The images located at the img folder. The suggested sizes are 150x150 px for the avatar and 32x32/16x16 px for the favicon.


