It's a development tool for creating static html with sass

The whole set up is accomplished by utilizing webpack4

-For development
Code all your source code under /src folder
If you want to add more sass/scss files. Remember to import your files to /src/index.js. Otherwise webpack won't include the new files.

--Watch development
The tool also comes with "watch" feature
Run "npm start". The tool will set up a dev server, and keep watching on all the files changes under / src folder
Under dev mode. All the changes won't be built, the dev server will save it in memory.

--Production
Run "npm run build". The tool will bundle all the files under /src folder into main.js in /dist folder
If you want to deploy your code. Just grab all the files under /dist folder and put it on your server
