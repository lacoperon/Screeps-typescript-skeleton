I don't know if there are any people interested in typescript here but I thought I would share the first version of my screeps.d.ts file, I've also included a gulpfile that will compile and upload your script to the 'dev' branch. You need to have a 'secrets.js' file in the same directory that exports an object with 'email' and 'password' for you screeps account. Remember to NOT include secrets.js in your git repo. I recommend using microsofts new Visual Studio Code for editing with support for typescript intellisense and gulp integration.
Requirements to build: node and npm gulp gulp-typescript tsd(for lodash typings)
I'm sure there are lots of improvements that could be made, this is my first shot at a d.ts file and I didn't try to make the game objects extendable.
I also kinda just gave up on documenting halfway through, yeah sorry :P.