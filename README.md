# dl-from-scratch-polynb


![null](https://camo.githubusercontent.com/94969f2a173108a544ef0a5cf7a515dbc3beacdc/68747470733a2f2f6c68352e676f6f676c6575736572636f6e74656e742e636f6d2f37587176324a7634334f7543573769366d786e53786a7577536a77314634347a59546443764e542d4e7364696b6e565f7731625f694750472d7a5371474d3633704144414f4d4f6946585666714863656d416a305f6c5a306876564135564a486a4a4f4474754f7968492d75724c3639386e50336f36314a654e4d4a61346e5f65417269345678444a5967)<br>

<br>

This is a polynotebook. See https://polynote.org/ for details.


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