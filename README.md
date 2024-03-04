# Prompt Engineering Techniques

## Getting started

### Jupyter Installation

If you use [conda](https://docs.conda.io/en/latest/), [mamba](https://mamba.readthedocs.io/en/latest/), or [pip](https://docs.python.org/3/installing/index.html), you can install JupyterLab with one of the following commands.

- If you use conda:
  ```shell
  conda install -c conda-forge jupyterlab
  ```
- If you use mamba:
  ```shell
  mamba install -c conda-forge jupyterlab
  ```
- If you use pip:
  ```shell
  pip install jupyterlab
  ```
  If installing using `pip install --user`, you must add the user-level `bin` directory to your `PATH` environment variable in order to launch `jupyter lab`. If you are using a Unix derivative (e.g., FreeBSD, GNU/Linux, macOS), you can do this by running `export PATH="$HOME/.local/bin:$PATH"`. If you are using a macOS version that comes with Python 2, run `pip3` instead of `pip`.

For more detailed instructions, consult the [installation guide](http://jupyterlab.readthedocs.io/en/latest/getting_started/installation.html).

### Environment

The project uses `dotenv`. So you should either create `.env` file in the project root with the following properties or export them as environment variables.
```text
OPENAI_API_KEY=sk-...
GOOGLE_CSE_ID=...
GOOGLE_API_KEY=...
```

Create OpenAI API Key using this [guide](https://platform.openai.com/docs/quickstart).

Create the GOOGLE_API_KEY in the Google Cloud credential console (https://console.cloud.google.com/apis/credentials) and a GOOGLE_CSE_ID using the Programmable Search Engine (https://programmablesearchengine.google.com/controlpanel/create). 

