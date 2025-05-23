# Meta-Programming Project

You can find the instructions of the project in the file [meta-programming-project.ipynb](meta-programming-project.ipynb).

To submit your solutions, please modify the files [meta-normal.lp](./meta-normal.lp), [meta-constraints.lp](./meta-constraints.lp) and [weighted-many.lp](./weighted-many.lp).

You do not have to submit your translator `asp2dimacs`.

Every time you push a new commit, your solution will be tested automatically.

The timeout per instance is `60` seconds, and the actual command calls for the tests are:
* ``python3.9 ./test.py 60 many``
* ``python3.9 ./test.py 60 normal``
* ``python3.9 ./test.py 60 constraints``

For help, type `python3.9 ./test.py --help`.

After the tests are run, you will be able to see the results in the **Actions** tab:
* Select one of the runs, click in run-autograding-tests and go to the tabs "Print output"
