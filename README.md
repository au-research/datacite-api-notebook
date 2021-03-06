[![CITATION.cff](https://github.com/au-research/datacite-api-notebook/actions/workflows/main.yml/badge.svg)](https://github.com/au-research/datacite-api-notebook/actions/workflows/main.yml)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/au-research/datacite-api-notebook/blob/main/datacite-api.ipynb)

# DataCite API notebook

This repository contains a Python Jupyter notebook and associated files that can interact with the [DataCite Member REST API](https://support.datacite.org/reference/introduction)
to perform the following functions:

* Mint draft DOIs
* Publish draft DOIs
* Hide published DOIs
* Delete draft DOIs
* Download metadata for existing DOIs
* "Sanitise" downloaded metadata to...
* Update metadata for existing DOIs

Use of this notebook requires you to be a DataCite Member and have a username and password to access the API. This is the same username and password you use to
log into Fabrica.

See the notebook itself `datacite-api.ipynb` for embedded documentation on how to use it, including initial configuration. 

It was developed on AARNet's CloudStor SWAN platform with the intention to remove as many barriers to reuse as possible.

# Disclaimer

DOIs are persistent identifiers and, like puppies, need to be cared for on a long-term basis. This notebook is intended to be a demonstration of the DataCite
API's capabilities and is not suitable for incorporation into data workflows. Ideally, DOI operations should be integrated into existing (or new) sustainable
data repositories.

# Getting started

SWAN is not intended for intensive workloads so can sometimes take a little time to complete tasks. This notebook can run in any suitably-configured Jupyter environment.

## Creating a copy of the notebook

1. Go to [AARNet CloudStor SWAN](https://cloudstor.aarnet.edu.au/plus/apps/swanviewer/home) and log in with your AAF (institutional) credentials.
2. Start a SWAN session
3. From the Launcher, open a Terminal (if you don't see the Launcher select File -> New Launcher)
4. At the command prompt, copy and paste (`Ctrl` or `Cmd` + `v`) the following commands, one line at a time:
```
cd cloudstor
git clone https://github.com/au-research/datacite-api-notebook
```

## Launching the notebook

1. In the file navigation tree on the left, double-click `cloudstor` and then `datacite-api-notebook`
2. Double click `datacite-api.ipynb` to launch the notebook in a new tab.

## Updating to the latest version of the notebook

1. Go to [AARNet CloudStor SWAN](https://cloudstor.aarnet.edu.au/plus/apps/swanviewer/home) and log in with your AAF (institutional) credentials.
2. Start a SWAN session
3. From the Launcher, open a Terminal (if you don't see the Launcher select File -> New Launcher)
4. At the command prompt, copy and paste (`Ctrl` or `Cmd` + `v`) the following commands, one line at a time:
```
cd cloudstor/datacite-api-notebook
git checkout .
git pull
```
