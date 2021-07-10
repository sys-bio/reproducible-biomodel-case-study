# Reproducible case studies from BioModels

## Set up
- ``python -m venv rcs``  # Create a python virtual environment
- ``source rcs/bin/activate``  # Activate the virtual environment
- ``pip install -r requirements.txt``  # Install in the virtual environment
- ``deactivate``   # Exit the virtual environment

## Start a session
- ``source rcs/bin/activate``  # Activate the virtual environment
- ``jupyter lab``  # Start jupyter labs
- Copy the URL shown in the terminal session into your web browser

## Open a notebook
- Use the left pane to select the notebook
- Double click on the desired notebook
- To run the notebook, use the Jupyter menu: ``kernel>Restart kernel and run all cells``

## End a session
- ``deactivate``   # Exit the virtual environment

## Building the book
- rm -rf reproducible-biomodel-case-study/_build
- jupyter-book build reproducible-biomodel-case-study 
