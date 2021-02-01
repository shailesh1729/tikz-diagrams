# tikz-diagrams
Diagrams using TikZ 

Some of the diagrams depend on styles and commands defined in
my personal packages and tikz libraries. These are available
from https://github.com/shailesh1729/articles .
Please check the *texmf* folder. 

Generating PNG image from PDF::

    convert -density 300 file.pdf -quality 90 file.png


Batch Processing::

    mogrify -format png -alpha off -density 300 *.pdf -quality 95

