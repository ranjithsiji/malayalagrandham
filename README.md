Malayala Grandha Vivaram
========================

Sourcecode and database of malayalagrandham.com der 
Django source is licensed under AGPLv3
Gandham DB is licensed Under GPLv3


Malayalam Grandham is a project intended to make available reliable bibliographic information on all Malayalam books published in Kerala and elsewhere. This Open data set contains Complete bibliography data from first Impression to 1995. This project wants to add following features to Malayalagrandham DB and build it as a bibliography web service

Facility for adding/linking copyright expired books to malaylagrandha vivaram
Adding ISBN & ISBN based seller discovery
Building Interface for Publishers through with they can contribute their publication bibliography .
Similar module for Libraries . That will be added to found in library section of each book
A module for building qr code of bibliography with a malayalagrandham link
Crowd sourced way for input and an approval queue interface for submissions.
MARC21 and MARCXML support
A dynamic visualisation interface for book information browsing
proper API , and app work flow documentation


File structure
--------------

server/passenger_wsgi.py   => Server configuration required in production mode.

db/smc_bib.sql.gz 				=> DB Dump as on 6th April 2013. 

grandham/         				=> Source


TODOs
-----
06-04-2013
----------
Bump up the Django version - will change all the directory structure.

Error handling - Currently the error handling is very minimum.

Follow CURD - Search is currently POST and not GET. Look out for more.

Pagination - Search results are not paginated.

Better layout - Work on a better layout.

Optimization - Coding was done without caring much about best practises nor is it optimized. 



Credits
-------
    Centre for South Indian Studies, Thiruvanathapuram
    Beehive Digital Concepts, Cochin
    Swathanthra Malayalam Computing (SMC)
    Compilation and General Editor: K.M. Govi
    Structuring and Classifying: K.H. Hussain
    Programming: K.P.N. Unni (Kriyate)
    Systemization: Mahesh M. (Kriyate)
    Project Co-ordination: Dr. R. Raman Nair

MalayalaGrandhaVivaram Task Force on Bibliographic Data Updation
----------------------------------------------------------------
    K.M. Govi (Chairman)
    K.H. Hussain (Convenor)
    Lalitha Lenin
    Dr. R. Raman Nair
    K. Rajendran
    P.M. Abdul Kadir
    Anivar Aravind
