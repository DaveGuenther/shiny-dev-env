# shiny-dev-env
This is a repo that contains a requirements.txt and a shiny dev environment with plotly.


## Installation
Create a python environment and then add the requirements.txt.  Some of the libraries have dev versions installed so that you can run shiny apps and debug into shiny library code.  Be sure to set the Python Debugger settings option "Just my code"= False so that svs code debugs into Shiny code

```
python -m venv .venv
pip install -r requirements.txt
```
