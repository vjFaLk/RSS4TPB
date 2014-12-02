RSS4TPB
=======

A Flask web app written in Python to generate RSS feeds from ThePirateBay and output as XML

- Heavily based on the script made by Camporez -
https://github.com/camporez/tpb2rss/blob/master/tpb2rss.py
- It's modified(Quite haphazardly) to work with Flask as a web app on Google App Engine
- Used by my torrent searching app, QuickBit, to quickly look up torrents and download them.


Usage
======
To use this on Google App Engine, you just need set the script up and add the libraries below in 'app.yaml'
For using it locally you'll need to setup the libraries below using pip or whatever you use. 

libraries:
- name: jinja2
  version: "2.6"
- name: markupsafe
  version: "0.15"
- name: lxml
  version: latest

