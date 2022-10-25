[//]: # (
    This file is the DAS data introduction tutorial made for workshop in UNAM, Mexico.
    Yang Li
    Oct 10, 2022
    )


# Intro to DAS Data 
To get started, you will need to install Anaconda and create an environment with some Python Modules related to our demonstration.


# 0. Installation

This tutorial is written in the programming language of [**Python**](https://www.python.org/). We create this tutorial based on [**Jupyter Notebook**](https://www.python.org/), which is a web-based interactive computing platform. To get access to Jupyter Notebook, we recommend you to install the open-source distribution of Python called [**Anaconda**](https://docs.anaconda.com/).
- [Installing on Windows](https://docs.anaconda.com/anaconda/install/windows/)
- [Installing on macOS](https://docs.anaconda.com/anaconda/install/mac-os/)
- [Installing on Linux](https://docs.anaconda.com/anaconda/install/linux/)

# 1. Creating a Python environment

A`.yml` file is provided in order to create a Python environment using conda to run the correspondeding .ipynb file. This environment can be created by excuting the following command:

```conda env create -f env_das.yml```

After generating this environment, you may activate it use:

```conda activate um_das_intro```

To launch Jupyter Notebook, just run:

```jupyter notebook```

# 2. Download data from Globus

If you never used globus before, try:

- create a [globus ID](https://www.globusid.org/create?viewlocale=en_US)
- Install [Globus Connect Personal](https://www.globus.org/globus-connect-personal)
- Download [data](https://app.globus.org/file-manager?origin_id=706e304c-5def-11ec-9b5c-f9dfb1abb183&origin_path=%2FDASworkshop%2F)


**DASworkshop** folder in Globus include DAS data we used for this demo. You could also get access to more DAS data in **PubDAS** folder. More details about [PubDAS](https://eartharxiv.org/repository/view/3574/) can be found in the paper.



