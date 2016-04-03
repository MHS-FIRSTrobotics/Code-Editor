# Mustang Robotics Code Editor

Just need something in a pinch, or have an URL with Java code you want to play with? This may be perfect for your needs.
Nothing is stored on the servers (besides the code to load this), instead your code is fetched from remote resources like GitHub,
and such, or is encoded directly in the URL of the page you are visiting (warning: the URLs get long quickly!).

## URL Parameter tags:
- **c** this is your Base-64 encoded JSON'ed code, don't change the automatically generated code without the proper tools
- **url** this is the URL for the code you want to see, served from a GET request to the URL (this is ignored if c is specified)
- **gh** work with a file directly on GitHub, this follows the standard format ```username/repoName```. The branch can then
be appended to the repo name with a ```!``` (example: ```ftctechnh/ftc_app!beta```). The file you want can then be specifed
by a ```>``` after all other parts (excluding the file path). This would look something like ```ftctechnh/ftc_app>build.gradle```
- **br** the Git branch of the GitHub repo, requires **gh**. Defaults to ```master``` if not otherwise specified
- **gp** the path to the file you want in the repo, defaults to ```README.md```

## Usage:
Use like any other code editor, except keep in mind that Ctrl-M (Command-M on Mac) creates the URL for your own purposes.

Feel free to play with this code, or visit https://mustangrobotics.club/editor.html for an example!