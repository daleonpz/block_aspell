# Description
Use [gnu aspell](http://aspell.net/) on a block of text from line N to M. 

# Use and requirements
- Use: 
```sh
    Usage: 
        [-n from] [-m to] [-f FILENAME]
```

- You need `aspell`
- How to install

```sh
$ git clone https://github.com/daleonpz/block_aspell.git
$ cd block_aspell
$ chmod +x block_aspell.sh
$ export PATH="$PATH:YOURPATH"
``` 

- You can also add the path to your `.bashrc` to make it permanent


# TODO
- Add language support (pass language option to aspell)
- I want to avoid the use of a TEMP file

