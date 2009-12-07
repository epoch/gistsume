# Gistsume

Crib another user's entire Gist-stash for backup purposes or what-have-you.

* If the Gist already exists as a repo, it'll pull to get latest.
* Right now it only consumes your public gists due to limitations in GitHub's Gist API

## Usage

$ *gitsume.rb* *username*

    jp@populuxe:~$ gistsume.rb jpignata
    Pulling jpignata-gists/gist-250480 
    Pulling jpignata-gists/gist-241231 
    Pulling jpignata-gists/gist-228912 
    Pulling jpignata-gists/gist-223279 (http://coderack.org/users/jpignata/entries/70-rackgeocities)
    Pulling jpignata-gists/gist-223275 
    Pulling jpignata-gists/gist-223263 
    Pulling jpignata-gists/gist-220995 
    ...

    jp@populuxe:~$ gistsume.rb wycats
    Cloning wycats-gists/gist-249491 
    Cloning wycats-gists/gist-249473 
    Cloning wycats-gists/gist-247701 
    Cloning wycats-gists/gist-247677 
    Cloning wycats-gists/gist-245698 
    ...

    jp@populuxe:~$ gistsume.rb parishilton
    Gist index for parishilton not found.
