# pryify-script
Script to change console from irb to pry in DBC challenges

## Installation
You can install in two ways. If you intend to keep the cloned repository on your computer, create a symbolic link in your /usr/local/bin folder. Pro: the script you run gets update every time you pull from this repo. Con: if you delete the repo, it breaks the script.

```shell
chmod 755 ./pryify
ln -s ./pryify /usr/local/bin
```

Alternately, you can copy the actual script into your /usr/local/bin folder. Pro: you can delete the repository and go on with your life! Con: no auto-updates when you pull from github.

```shell
cp ./pryify /usr/local/bin
chmod 755 /usr/local/bin/pryify
```

## Usage
Simply cd into the base directory of the challenge repo (`cd ~/ar-teams-and-leagues-challenge` for example) and type `pryify`!
