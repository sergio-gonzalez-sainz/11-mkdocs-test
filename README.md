# 11-mkdocs-test

MkDocs is a fast, simple and static site generator that's geared towards building project documentation. Documentation source files are written in Markdown, and configured with a single YAML configuration file.
## Requirements

MkDocs requires a recent version of Python and the Python package manager, pip, to be installed on your system.

You can check if you already have these installed from the command line:

`$ python --version`<br>
Python 3.8.2 <br>
`$ pip --version`<br>
pip 20.0.2 from /usr/local/lib/python3.8/site-packages/pip (python 3.8)


## Installation


### Installing pip
If you're using a recent version of Python, the Python package manager, pip, is most likely installed by default. However, you may need to upgrade pip to the lasted version:

`pip install --upgrade pip`<br>
If you need to install pip for the first time, download get-pip.py. Then run the following command to install it:

`python get-pip.py` <br>

### Installing MkDocs
Install the mkdocs package using pip. To install MkDocs, run the following command from the command line:

`pip install mkdocs`

You should now have the mkdocs command installed on your system.
Run mkdocs --version to check that everything worked okay.

`$ mkdocs --version`<br>
mkdocs, version 1.2.0 from /usr/local/lib/python3.8/site-packages/mkdocs (Python 3.8)

### Local server 
Make sure you're in the same directory as the mkdocs.yml configuration file, and then start the server by running the mkdocs serve command:

`mkdocs serve`
