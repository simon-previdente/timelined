#Timelined
----------
Timelined is a customizable CSS-only vertical timeline.

## Quick start

### Grab the compiled code
The compiled SCSS code is the `css` directory, which will work fully work without the need of compiling anything. Don't forget to grab the `index.html` file too, to get the idea of how the tool works.

### Compiling
The styling is done with SCSS and you can compile it with any proper tool (I use [node-sass](https://github.com/sass/node-sass)). There are a couple of variables and other stuff to make the customization faster.

### Usage

#### Basic structure

	<div class="timeline gray-blue"> <!-- Main element container -->
		<div class="timeline-block">	<!-- Single block -->
			<div class="timeline-icon"></div> <!-- Icon on the timeline -->
			<div class="timeline-content"> 
				<p> Any content </p> <!-- Content -->
				<div class="timeline-date">Yesterday</div> <!-- Date -->
			</div>
		</div>
		...
	</div>

##### Additional options
Some additional customization is available by adding additional classes to the main container element `.timeline`:

* `.timeline-left` - The line is on the left while the content is always on the right;
* `.timeline-alternating` - Blocks are alternating between left and right of the line;
* `.timeline-collapsing` - The timeline automatically switches to `timeline-left` mode when the container is small (800px, by default).

#### Additional schemes

Schemes are a quick way to change the color of the line, icon on the timeline and  border of the block. The names are self-explanitory: `gray-red`, `gray-blue`, `blue-yellow`, `purple-flirt`.
Adding the scheme name as a class on the main container will do the job.

## Demo - http://timelined.andriaus.lt/

## License
The MIT License (MIT)

Copyright (c) 2016 Andrius Ševčenko

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

