# svg2dio
Converts SVG files to drawio/diagrams.net format  
You can import svg into diagrams.net, but you can't change the fill color, stroke color or stroke width.  
importing files converted with this tool will give you options to customize the svg colors in the style panel.

![screenshot](https://github.com/msdavid/svg2dio/blob/main/img/screenshot.png)


git clone https://github.com/msdavid/svg2dio.git  
cd svg2dio  
chmod +x svg2dio  

usage: svg2dio [-h] [-f] [-t] [-w] [-s] [-o] [-d] filename

positional arguments:  
  filename              input file  

optional arguments:  
  -h, --help            show this help message and exit  
  -f , --fill-color     Fill fall-back color default: D4D4D4  
  -t , --stroke-color   Stroke fall-back color default: D4D4D4  
  -w , --stroke-width   Stroke fall-bak width default: 5  
  -s , --size           Object size default: 100x100  
  -o , --output-file    Output file name  
  -d, --debug           print resulting root svg (xml)  


example:   
./svg2dio -s 200x200 -f 4A4A4A -w 3 file.svg -o myfile.dio  


