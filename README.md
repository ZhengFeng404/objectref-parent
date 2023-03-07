# eliza-parent

Parent repository for the object referencing App.

This repository contains all components as _git_ submodules and can be used as the
root to execute [build commands](https://github.com/leolani/cltl-build/tree/main/make) that are run on the components.

## Check-out

To check out all code needed for the Eliza App, clone this repository including all submodules:

        git clone --recurse-submodules -j8 <repo URL>


## Run the application

Checkout the repository as described in [Check-out](#check-out). Then go to the
repository root, build the project, activate the virtual environment for the
Python application and run it. Altogether:

        git clone --recurse-submodules -j8 <repo URL>
        cd objectref-parent
        make build
        cd <app-dir>
        source venv/bin/active
        cd py-app
        python app.py


