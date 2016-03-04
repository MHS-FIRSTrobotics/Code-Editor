# Mustang Robotics Code Editor

Just need something in a pinch, or have an URL with Java code you want to play with? This may be perfect for your needs.
Nothing is stored on the servers (besides the code to load this), instead your code is fetched from remote resources like GitHub,
and such, or is encoded directly in the URL of the page you are visiting (warning: the URLs get long quickly!).

## URL Parameter tags:
- c: this is your Base-64 encoded JSON'ed code, don't change the automatically generated code without the proper tools
- url: this is the URL for the code you want to see, served from a GET request to the URL (this is ignored if c is specified)

## Usage:
Use like any other code editor, except keep in mind that Ctrl-M (Command-M on Mac) creates the URL for your own purposes.

Feel free to play with this code, or visit https://mustangrobotics.club/editor.html for an example!