PHP placeholder images
======================

A little PHP placeholder image generator (GD support must be enabled).

Usage (all parameters are optional): <br>
&lt;img src="placeholder.php?size=400x150&bg=eee&fg=999&text=Generated+image" alt="Placeholder image" /&gt;

See demos: http://skymaiden.github.io/php-placeholder-images/


Inspired by http://placehold.it/

# Placeholder-cli (cli option)

placeholder-cli is a placeholder script which works in command line.

## how to use

run `./placeholder-cli (press enter)`

it will generate images directory (if not present) in the same directory in which the plcahoder-cli is present and then it will create an 100x100 size png image.

### cli options

`placeholder-cli [size=] [fg=] [bg=] [fname=] [text=""]`

* **size=** widthxheight(by default 100x100)

* **fg=** any hexadecimal color

* **bg=** any hexadecimal color

* **fname=** file name without        extension

* **text=** text which you want to print on image

### example
`./placeholder-cli size=200x200 fname=image1 text="hello, world" bg=#000000 fg=#ffffff`

The above command will generate png image of size 200(width)x200(height) with white text color, black background, text hello world, name image1.png

License
-------
MIT: http://skymaiden.mit-license.org
