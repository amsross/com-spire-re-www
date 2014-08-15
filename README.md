#[spire-re.com](http://www.spire-re.com) [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/) [![Build Status](https://travis-ci.org/amsross/com-spire-re-www.png?branch=master)](https://travis-ci.org/amsross/com-spire-re-www)

1. Install global dependencies
	```
	gem install jekyll && npm install -g grunt-cli
	```

2. Install project dependencies
	```
	npm install
	```

3. Fire listeners
	```
	screen -S grunt -d -m grunt dev
	screen -S jekyll -d -m jekyll serve --watch
	```

4. Do work...
	```
	vi <filename>
	git add <filenames>
	git commit
	git push origin master
	```

5. Kill listeners
	```
	screen -X -S grunt quit
	screen -X -S jekyll quit
	```

6. Final build (optional)
	```
	grunt build
	```
