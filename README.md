# dl-from-scratch-polynb

This is a polynotebook. See https://polynote.org/ for details.

How to use:
- clone this repo in a folder `my-folder`
- if it does not exist yet, create config.yml by copying config-template.yml
- edit config.yml, and add a new storage mount:

```
storage:
  dir: notebooks
  mounts:
    dl-from-scratch:
      dir: my-folder/dl-from-scratch-polynb
```
Then (re-)start polynote, and select the notebook from the `dl-from-scratch` mount.
