# Bleak

Doing some upgradtion in Bleak theme for [Ghost](http://ghost.org),
Orginally coded by [Peter Amende](http://zutrinken.com/).

---
Please upgrade your ghost to 0.9 or more, to use it as a Progressive Web App.

This theme is using manifest.json file which only supports in 0.9 or higher version of Ghost

***Hint:*** This theme works with AJAX, so it won’t work with multiple domains properly! Use redirects to only one domain instead. Also make sure you haven’t jQuery injected in your footer due to [Ghosts migration method](http://dev.ghost.org/no-more-jquery/). This can break the layout!_

## Demo

* [Blog](http://abhiy.com)
* [Post](http://www.abhiy.com/single-sign-on-remote-authentication-in-freshdesk-by-python/)
* [Tags](http://www.abhiy.com/tag/python/)
* [Author](http://abhiy.com/author/abhishek)

## Features

* Responsive layout
* Blog navigation
* Post navigation
* Cover images for blog, tag and author archives
* Featured posts style
* Automatic code syntax highlight and line numbers
* Disqus support
* Sharing buttons

## Setup

To enable [Disqus](https://disqus.com/) comments go to your blogs code injection settings and add `<script>var disqus="YOUR_DISQUS_SHORTNAME";</script>` to your blog header.

## Development

Install [Grunt](http://gruntjs.com/getting-started/):

	npm install -g grunt-cli
	
Install Grunt modules:

	npm install

Install [Bower](http://bower.io):

	npm install -g bower

Install Bower components:

	bower install

Build Grunt project:

	grunt

Distribute Grunt project:

	grunt build

## Copyright & License

Copyright (C) 2015-2016 Peter Amende - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
