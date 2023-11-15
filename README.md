# Shell_scripting_notes

## View the history of commands

LINUX OS
```sh
  cat ~/.bash_history
```
MAC OS

```sh
  cat ~/.zsh_history
```

## Bash notes
```sh
  
```

## TCSH notes

### If directory does not exists, create one
```sh
  set dir = "A directory"
  if (! -d "$dir") then
    mkdir
  endif
```

Putting a directory between a quote is necessary for the shell to grab the whole string especially the path contains space. Also, it is a good practice.  
