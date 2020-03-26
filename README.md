# dl-from-scratch-polynb


![null](https://lh4.googleusercontent.com/cu4A1znRGfRIUn0Bt_SREExhhQYhC2KKO5czYlqJaiN-SL3lrHgfmnHMBN7_9wnWVfSdY_uEvq5HvY3LT-n4X7st9PAB96qUMkPx-0XLhZzW5O0tOerQrqaqu0gPKkdgEIW8LIsqTew)<br>

<br>

This is a polynotebook. See https://polynote.org/ for details.<br>


How to use:


* clone this repo in a folder `my-folder`
* if it does not exist yet, create config.yml by copying config-template.yml
* edit config.yml, and add a new storage mount:

```
storage:
  dir: notebooks
  mounts:
    dl-from-scratch:
      dir: my-folder/dl-from-scratch-polynb
```

Then (re-)start polynote, and select the notebook from the `dl-from-scratch` mount.