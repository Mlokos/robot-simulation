# robot-simulation

## install poetry
https://python-poetry.org/docs/
## set up poetry
`cd robot-simulation` <br>
`poetry install`

## install mujoco
https://github.com/openai/mujoco-py#install-mujoco

## Run
**export environment variable:** <br>
`export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/home/mlokos/.mujoco/mujoco210/bin` <br>
**run trainer inside poetry virtual environment:** <br>
`poetry run python trainer.py`


## Troubleshooting
**FileNotFoundError: [Errno 2] No such file or directory: 'patchelf'** <br>
`sudo apt install patchelf`