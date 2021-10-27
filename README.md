# TechTestWH

You will need to complete two assignments, both of which should take 2 hours to fully complete. Be thoughtful and look for edge cases.

It doesn't matter in which order do you complete these tasks. Or even if you complete them at all. A well documented and explained half-solution is better than a complete, but messy one.

## Task 1: Visualization with seaborn and pandas.

Load the `solar_mesh.csv` file as a dataframe with pandas. In the file the first row and the first colum show binned coordinates (over germany). Your task is to graph a heatmap with the weights being the values withing those coordinates (or coordinate bins). (preferabily with seaborn)

As an example at the coordinate bin  (47.511, 47.601], (6.061, 6.219], the weight should be 0, but at (50.743, 50.825], (6.061, 6.219] the weight should be 7720. For bonus points you can normalize all the weights.



## Task 2: Manipulating data

Here the coordinates themselves don't matter at all. the only thing important is their weights.
Bin the dataframe's 'weights' into five equeal sized bins, where the bins are counted as = 0 | max/4 | max/2 | max/4*3 | max.
Plot this binned data as a histogram using seaborn or plt.
 
 
 
 
 What and how to "submit":
 - Create a new private git repo to which add user `qty0`.
 - The repo should have (at least) two jupyter notebooks for the two tasks.
 - The repo should have a `requirements.txt` for it's virtual env. !Hint -> `pip freeze > req.txt`.
 
 
 If you have any questions, notice any problems, feel free to contact our cto: peter@digitalyn.dk
