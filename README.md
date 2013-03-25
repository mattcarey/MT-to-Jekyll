MT-to-Jekyll
============

Movable Type to Jekyll template

To export all your Movable Type entries into YAML files for importing into Jekyll, do the following:

1. Create a new archive template, using the 'entry' type

2. Grab the template code from this repo and paste it into the template box

3. Set the archive mapping to use the following (custom option) and keep publishing to 'static'

jekyll/<mt:entrydate format="%Y-%m-%d">-<mt:entrytitle dirify="-">.md

4. Save the template

5. Republish the Movable Type blog

You will now have a folder called 'jekyll' at the root level of your MT site. Within the folder are all the entries in Jekyll compatiable YAML format.

Copy all the files into the _posts folder in your jekyll install.