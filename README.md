# Using LLM to Query Data

Materials for the "Using LLM to Query Data" workshop at the ODSC 2025 conference. 

WIP...🏗️


<figure>
 <img src="images/boston.png" width="100%" align="center"/></a>
<figcaption> Boston 3D map (created with Midjourney)</figcaption>
</figure>

<br>
<br />

Session info: https://odsc.com/speakers/using-llm-to-query-data/

When 📆: May 15, 2025, at 2:00 PM EDT


## Prerequisites

You will need to set up your Python virtual environment to follow along with the workshop materials. You can either set a virtual environment using your preferred method (venv, uv, conda, etc.) or use Docker.

### Virtual Environment

The workshop environment is available on the [requirements.txt](https://github.com/RamiKrispin/osdc-2025-llm-workshop/blob/main/docker/requirements.txt) file under the `docker` folder. 

Here is how you can set your virtual environment with uv. This required uv to be installed. 
```shell
uv venv --python 3.11
```

We will activate the the virtual environment and install all the dependencies for this workshop:

```shell
source .venv/bin/activate
uv pip install  --no-cache-dir -r docker/requirements.txt
```

You can validate if the process was completed successfully by running the `uv pip list` command:

```shell
uv pip list                                                                       ok  6s  osdc-2025-llm-workshop py
Package                   Version
------------------------- --------------
annotated-types           0.7.0
anyio                     4.9.0
appnope                   0.1.4
argon2-cffi               23.1.0
argon2-cffi-bindings      21.2.0
arrow                     1.3.0
asttokens                 3.0.0
async-lru                 2.0.5
attrs                     25.3.0
babel                     2.17.0
...
...
urllib3                   2.4.0
wcwidth                   0.2.13
webcolors                 24.11.1
webencodings              0.5.1
websocket-client          1.8.0
wheel                     0.45.1
widgetsnbextension        4.0.14
zipp                      3.21.0

```

### Docker

Alternatively, you can use the workshop's image which contains all of the dependencies and is ready to go:
```shell
docker.io/rkrispin/python-odsc-2025:arm64.0.0.1
```

If you are using VScode, I recommend using the VScode Dev Containers extension with the default container configuration.settings as defined in `.devcontainer/devcontainer.json`.





