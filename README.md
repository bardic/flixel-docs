flixel-docs
===========

This is the main location for HaxeFlixel documentation. Pull requests from this location will be pushed to the live website periodically, so please help us improve the HaxeFlixel docs.

## Contents

* The "main" documentation available on [haxeflixel.com/documentation](http://www.haxeflixel.com/documentation).
* The API documentation.

### Main documentation

The main documentation is made up of `*.html.md` files with a numerical prefix specifying the order listed on the [docpad website](https://github.com/HaxeFlixel/haxeflixel.com). Additional pages can be added using the same extension and using a header specifying the title as seen in the other pages.

The markdown syntax used in the docs is the  [GitHub-Flavored-Markdown](https://help.github.com/articles/github-flavored-markdown), thus it's very convenient to directly edit the files via GitHub's web editor. 

### API documentation
	
* ####Install [chxdoc](https://github.com/ibilon/chxdoc) for Haxe 3
	
		haxelib git chxdoc https://github.com/ibilon/chxdoc
	Move your cwd to this relative path of the project:
		
		cd ./api/chxdoc-gen
		haxelib run chxdoc install
	
* ####Generate the API docs
	
		haxe docs.hxml

The docs will now be generated in the `./docs` folder. 