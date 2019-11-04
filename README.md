# Setup
Change directory to Pokemon-Showdown. Run "node build". (If you haven't installed node yet, you will need to). Then cd .. back to the previous directory. If you want to load example weights, rename save\_stable.p to save.p. If you want to start training from scratch, set the resume variable in pkmn.py to "False". To start learning, run "python pkmn.py". Note that env_pkmn.py, which pkmn.py depends on, uses a relative path to get to its dependences in Pokemon-Showdown. So if you run this from some other directory, it will be broken.
