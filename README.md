# Mirroring from SVN repo to GitHub

## Some Limitations
1. Large Files not tracked (see `.gitignore`)
    1. Some error happens about authentication

## Usage for copying to new repo
1. Need to update restrictions to have Actions write to repo
    1. Settings -> Actions -> General -> Read & Write
1. Need to add secrets
1. Need to add file `authors.txt` to convert SVN username to git user and email
1. Need to add file `last_revision.txt` to track the last revision that was pulled from SVN

## TODO
- when in CBECC-COM repo, test git LFS with everything (not ignoring files) to assure that all files are tracked
- expand `authors.txt` file as needed to capture more/all users
