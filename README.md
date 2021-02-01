# tikz-diagrams
Diagrams using TikZ 


# Generating Images

::

    convert -density 300 file.pdf -quality 90 file.png


Batch Processing::

    mogrify -format png -alpha off -density 300 *.pdf -quality 95