# svg2dio
Converts SVG files to drawio/diagrams.net format


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


