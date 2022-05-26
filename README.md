# Notes app - User-Guide

# Dependencies
- yargs - npm install yargs 
- chalk - npm install chalk@2.4.2

- yargs - Yargs helps to build interactive command line tools, by parsing arguments and generating an elegant user interface.chalk - It helps to customize the color of the output of the command-line output It helps to improve the quality of the output by providing several color options like for warning message red color and many more

# commands to run and description:

- Note: add all the commands in terminal or console.
- node app.js add --title="a" --body="b" -> adds the note , if command is not properly entered then throws the error.
- node app.js list -> displays the list the existing notes title in console.
- node app.js read --title="nodejs" -> Reads the note content by the tittle entered. value of title should be the existing title of notes. otherwise it throw NOTE NOT FOUND
- node app.js remove --title="a" -> Removes the note with a given tittle

# Note:
If we run the command without providing the required properties for add, read or remove commands.
It will show the brief information about that particular command like what are the required properties 
need to be add for getting the correct output for example: node app.js add/node app.js remove/node app.js read
