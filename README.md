Web-Folder-Indexer
==================

Creates an index.html file for the content of a folder and a subfolder, and allow to present certein file types inside the Web-GUI.
If an info file exist (should be json/dict), it will be visible in the folder's
page.

NOTICE: This script also makes sure all of the files are visible to the public.
(i.e. "chmod 755 <file>" for all the files)

Usage
==================
    index.py [directory, path_name]

- directory: The base directory to index (default: current directory)
- path_name: The path that will appear in the title of the page as the current path base (default: the folder name)

Example:
The command
    index.py ~/.www/files home/files
will create index for the folder files and its subfolders. The title of the page will be "home/files".

Author
==================
Liran Funaro - fonaro@cs.technion.ac.il