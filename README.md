explain-plz-data
================

This is the data for the [explain-plz](https://github.com/timroes/explain-plz) tool.

If you can add anything usefull to the data or want to modify explanations, please send pull
requests to that project.

The data should always aim to the most recent Android source code. So if projects have been
moved, this data won't work on older source code versions.

The data in this project is organized in two type of files:

The index file (`index.idx`) contains a list of all folders, that has an explanation.

Each line in this file must have the following format:

`folder/to/explain|explanation_filename.txt`

The lines must be sorted alphabetically after the folder they explain (just look at the
`index.idx` file to understand).

The first name is the relative path inside the Android source code, that should be explained
and the second parameter is a (freely chosen) filename of the explanation file for this folder.

The explanation file must be a `txt` file, containing the explanation.
Each line in that explanation should have a maximum of 80 to 100 characters.
