# CAMELOT-Colab
Proper Documentation Of Extracting Tables From Pdf Using Camelot On Google Colab With More Examples.

For Official Documentation click on below link - 
https://camelot-py.readthedocs.io/en/master/

for this tutorial, I have used Google Colab which easily accessable to all.
Lets Start-
we have to install some libraries on colab

!pip install ghostscript

!pip install camelot-py[cv]

!pip install excalibur-py

!apt install ghostscript python3-tk

!pip install pdf2image

!apt-get install poppler-utils 


For showing the Pdf, I have used Pdf2image here.

read_pdf function of camelot is used to extract the tables.

eg-

tables= camelot.read_pdf('foo.pdf')

You will find more examples here.

Its all about Camelot and their parameter. A proper paremeter gives you desired result.

Thank You So Much For Your time.


