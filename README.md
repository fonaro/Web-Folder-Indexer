Web-Folder-Indexer
==================

Creates an index.html file for the content of a folder and a subfolder, and allow to present certein file types inside the Web-GUI.

Usage
==================
index.py [directory, path_name]

This will create an index.html file for every folder in the subtree of the given
folder (or the current folder if not specified).
If an info file exist (should be json/dict), it will be visible in the folder's
page.

NOTICE: This script also makes sure all of the files are visible to the public.
(i.e. "chmod 755 <file>" for all the files)
