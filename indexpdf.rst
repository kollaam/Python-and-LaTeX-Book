.. test documentation master file, created by
   sphinx-quickstart on Thu Oct 29 11:15:52 2009.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

An introduction to Python and LaTeX
====================================

The  BSc Informatics course conducted by `University of Calicut <http://http://www.universityofcalicut.info>`_ is based completely on Free  Software. Students are required to study the Python programming language and also learn how to
prepare technical documents using LaTeX. Majority of the students have a computing background 
limited to using Microsoft Windows for simple tasks like web browsing. 
*An introduction to Python and LaTeX* has
the objective of providing a gentle introduction to computing to such an audience. 

Because most of the readers
would be either Mathematics teachers or undergraduate Math students, sample programs are structured around
simple mathematical concepts. No attempt has been made to go deep into language syntax - my experience  with conducting several
workshops for teachers has been that any attempt to introduce syntax elements whose application can't be demonstrated immediately
through simple math examples usually leads to confusion. So, this book will not be an ideal resource for people who wish
to master Python syntax and idioms in depth. There are plenty of great resources on the net for that, one of the best being
*Dive into Python* (available at  http://www.diveintopython.org).

This book is being updated continuously - the most recent version is available on the Internet
at this address: http://radiantbytes.com/books/python-latex


.. toctree::
   :numbered:

   src/chap1.rst
   src/chap2.rst
   src/chap3.rst
   src/chap4.rst
   src/chap5.rst
   src/chap6.rst
   src/chap7.rst
   src/chap8.rst
   src/chap9.rst
   src/chap10.rst
   src/chap11.rst
   src/chap12.rst
   src/chap13.rst
   src/chap14.rst
   src/appendix1.rst

License
--------
This book is published under the `GNU FDL <http://www.gnu.org/copyleft/fdl.html>`_

How to build the book from source
----------------------------------

This book is written using an excellent tool called `Sphinx <http://sphinx.pocoo.org/>`_. Sphinx
allows you to write in simple `restructured text <http://docutils.sourceforge.net/rst.html>`_ format -
the conversion to HTML (for display in a browser) as well as LaTeX (for printing) is done by Sphinx.
You are reading the Sphinx generated book right now!  Source files are available from 
`GitHub <http://github.com/pramode/Python-and-LaTeX-Book>`_.

A little bit about my book-writing work flow. I maintain a git repo on my home machine from where I
occasionally push to `GitHub <http://github.com/pramode/Python-and-LaTeX-Book>`_. I have another git
repository on my Linode slice which hosts the book - occasional pulls from github combined with
a build which directly delivers  HTML files to the web server's (I use Nginx - do try it out
if you find Apache to be a memory hog) static files folder is all that is needed to "publish" the book!



