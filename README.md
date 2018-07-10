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

# Merge (some-branch into master)
**$** git checkout master

**$** git merge some-branch

# Remove modified files or working directories (staged for commit)
**$** git reset --hard

# Clean untracked files (not flagged for commit)
# (CAUTION: Will delete files)
**$** git clean -f -d # remove untracked
**$** git clean -f -x -d # CAUTION: as above but removes ignored files like config.
**$** git clean -fxd :/ # CAUTION: as above, but cleans untracked and ignored files through the entire repo (without :/, the operation affects only the current directory)

