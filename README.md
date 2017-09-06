##soda inc.
#version 1

soda inc. is a fast and simply work model for webdesign projects with html5, sass, javascript and grunt.



#features
    -ready to go predefinited html, css files (meta tags, viewport, grid, google font import, fa icons linked)
    -configured, redy to go grunt.js, You have to only grunt and grunt plugins install.
    -multiple sass files,
    -automatic minificate html, css and js files,
    -automatic optimalize images (png, gif, jpg),
    -jshint
    -live preview wit browser-sync


#future roadmap
    -automatic generate sources map for css and js
    -clean with grunt sub-instructions
    -more styles (form for example.),
    -add grunt task for automatic generate favicons
    -add grunt task for automatic generate sitemap
    -webpack2 included,
    -maybe change grunt.js to branch or gulp?

#docs
catalog`s discription
-development - sources catalog with raw sources files.
-development/others - place for PSD, blueprints, mockups and others.
-distribution - catalog for publicate. all files after grunt tasks is lacated here.

#grunt installation instructions
(after node.js and ruby installation ofc. remember ruby-dev package!)
linux
write to your terminal in projects catalog:
npm install -g grunt-cli (global installation require admin privleges with su or sudo command.)
npm install grunt-cli --save-dev
npm install grunt-contrib-jshint --save-dev
npm install grunt-contrib-htmlmin --save-dev
npm install grunt-sass --save-dev
npm install grunt-contrib-uglify --save-dev
npm install grunt-contrib-watch --save-dev
npm install grunt-contrib-jshint --save-dev
npm install grunt-browser-sync --save-dev

#grunt using insctruction
in main catalog of project type in terminat:
"grunt" > for all task watch and browsersync too but without image optimalisation.
"grunt imagemin" for only images optimalisation and without watch and browsersync task.
"grunt distribution" for finished project (minifying all files, optimalisation images, debugged javascript, compilation and concatenation sass files without watch and browsersync task.
