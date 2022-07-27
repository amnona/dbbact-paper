# Jupyter notebooks for recreating dbBact paper figures

## Requirements:
* [Calour](https://github.com/biocore/calour)
* [dbBact-calour](https://github.com/amnona/dbbact-calour)

## How to run
Each figure subdirectory contains the jupyter notebooks and data required for recreating the figure.

Figure 6 contains code for the 16 biological example figures detailed in the supplementary materials

Since some subpanles in figure 3 (dbBact stats) require a lot of database querying they should be run on a local postgres dbBact server (noted in the relevant jupyter notebook).

For this notebook, you should run a postgresql server and the [dbbact-server](https://github.com/amnona/dbbact-server) rest-api locally.

Any problems/questions, please open an [issue](https://github.com/amnona/dbbact-paper/issues).

The dbBact website can be found at: [www.dbbact.org](https://www.dbbact.org)

Share and enjoy
