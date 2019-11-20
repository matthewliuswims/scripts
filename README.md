# Scripts
- for personal usage of scripts

## Setup
- set `$HOME/scripts` to be directory where scripts live in. https://askubuntu.com/questions/29589/chmod-ux-versus-chmod-x - this is so we can run scripts regardless of current directory.

write below code in `bash_profile` or which ever shell config file you are using.
```
PATH="$HOME/Pub-Scripts:$PATH"
export PATH
```

- in terminal `echo $PATH` and make sure `$HOME/Pub-Scripts` is present in the output path.
- make the script (e.g. `hello-world.py`)
- change permission of file to execute `chmod u+x` - https://askubuntu.com/questions/29589/chmod-ux-versus-chmod-x
- `hello-world.py` in any directory - it should work!


## Running scripts (python)
- just do `hello-world.python` (assuming everything is set up correctly)
- https://www.taniarascia.com/how-to-create-and-use-bash-scripts/
- https://stackoverflow.com/questions/40793101/how-do-you-make-a-python-script-globally-executable-osx

## Miscellaneous Resources
https://www.reddit.com/r/linux/comments/ayditr/chmod_cheatsheet/
