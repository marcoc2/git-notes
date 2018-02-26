# git-notes
Common git commands

## Fetch files from a submodule with a empty folder
**$** git submodule update --init

## Add external submodule
**$** git submodule add _**url**_

## Update repository recursively
**$** git submodule update --recursive --remote

## Reset a single file
**$** git checkout HEAD -- my-file.txt
