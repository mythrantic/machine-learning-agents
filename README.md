## AI simulations in unity
the pyproject.toml, README.md, .python_version and uv.lock is used to define the python version and packages you need to have beforehand. simply initialize the env and it will install the correct python and package if you are using uv: ```uv sunc```. then simply activate it 


to for example train after making the parameter file. google how. just run this command after activating the environment and going to the root of the project

```bash
mlagents-learn config/ppo/Basic.yaml --run-id=run1**
```

this is followed by the play button in unoty.

think of unity as the frontend
and ml-agents as the backend
