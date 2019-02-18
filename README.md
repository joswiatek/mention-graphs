Use this repository to generate mention graphs. 

# Set up #

1. Clone the repo
2. Set up a python virtualenv if you wish.
   1. `virtualenv my_virtual_env`
   2. `source my_virtual_env/bin/activate`
3. Install the dependencies.
   1. `pip install -r requirements.txt`
4. Fill in `rushees.txt` and `actives.txt` with the names of individuals and `mentions.txt` with edge directed relationships. 
5. Run the juypter notebook to import the data and generate graphs. (Optionally play with the node and edge sizes and colors.)
   1. `jupyter notebook mention-graph-notebook.ipynb` 