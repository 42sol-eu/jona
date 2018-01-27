# jona
python application package user interface and user experiance (pip deploy application, but without the commandline)

create a easy to use frame for providing python application deployment (the goal would be "pip deploy MyApp" like Glyph stated on PyCon2016

## Motivation
I am very invested in Python as a programming language. Since I have learned the magic of scripting languages starting with Perl during my thesis, way back. I converted to Python directly after I started working in 2003.

As Michael Kenedy in his gerat [Podcast "Talk Python To Me"](talkpython.fm) lately discusses are there two things that hinder Python development very much at the moment (in early 2018):
- Deployment of applications (on the various operation systems)
- A pythonic user interface (with a native look and feel)

Both seem to be addressed in the Beeware Project namely Toga for User Interface and Briefcase for Deplpoyment.

The goal of this project is not to reenvent the wheel, but to start at a point, where a beginner in development would feel comfortable to start - and a pro would enjoy not to type the same stuff over and over again.

## Architecture
Hence there is at the moment not the ideal choice to create an easy deploable application in Python this project will use Qt5 to fill in that gap until we have a good an usable solution.
I will also use the QT Installer Framework to supplement the Python-based Installers.

## Warning: This is a working project in early phase!
