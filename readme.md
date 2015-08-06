
###Gulp Tasks

#### Development Task
This task will compile all files from **\src** folder to **\dev** folder, and start the web server for development.

```
$	gulp
```

#### Components Development Task
This task will compile all files from **\src** folder to **\components** folder, and start the web server for component development.

```
$	gulp comp
```

#### Build Task
This task will compile all files from **\src** folder to **\dist** folder. Ready for distribution.

```
$	gulp build
```

##Folder structure
	+---components
	+---dev
	+---dist
	+---src
		+---fonts
		+---images
		+---js
		+---scss
		¦   +---components
		+---vendors

- **\src**: Where all project files are developed.
- **\components**: Where all  individual HTML components are developed.
- **\dev**: Where the compiled project and live develop web server runs.
- **\dist**: Where the static compiled project reside, after a build.
	
		
##Requirements:

###FrontEnd Develop
- [Git]
- [Node.js]
- [Ruby]
- [Compass] for [Ruby]
- [Gulp] for [Node.js]
- [Bower] for [Node.js]

**Note**: In some networks Node.js or bower fail to access the packages because the _git://_ protocole is blocked. A workaround is to configure **Git** to globally use the protocol _https://_ instead.

Jus open the git console and run this command:

	$ git config --global url."https://".insteadOf git://


###Misc
To view this document more easily, install chrome [Markdown Preview Plus] plugin.  
1. Set the extention .md to always opened in Chrome.
2. Give the addon permission to access local files on Chrome's extension page.
3. And setup the addon to display the markdown file using _"GitHub"_ theme.



[Markdown Preview Plus]: https://chrome.google.com/webstore/detail/markdown-preview-plus/febilkbfcbhebfnokafefeacimjdckgl?utm_source=chrome-app-launcher-info-dialog

[Git]: http://git-scm.com/download/win
[Node.js]: http://nodejs.org/dist/v0.12.4/node-v0.12.4-x86.msi
[Ruby]: http://dl.bintray.com/oneclick/rubyinstaller/rubyinstaller-2.2.2.exe
[Compass]: http://compass-style.org/install/
[Gulp]: https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md
[Bower]: http://bower.io/#install-bower
