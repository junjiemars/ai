# AI
 
## Development Environment

### Python

__Terminal__
* __virtualenv__: ```virtualenv --python=python<ver> --no-site-packages <venv-dir>```
* activate virtualenv: ```source <venv-dir>/bin/activate```
* install __ipython__: ```pip install ipython```
* install requirements: ```pip install -r <requirements.txt>```
* deactivate virtualenv: ```deactivate```

__VSCode__
* one way: 
```sh
source <venv-dir>/bin/activate
code
```
* another way: in _launch.json_,  ```"pythonPath": "${workspaceRoot}/<.venv-dir>/bin/python"```



## References

