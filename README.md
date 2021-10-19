# TechTestWH

You will need to complete two assignments, both of which should take 2 hours to fully complete. Be thoughtful and look for edge cases.


## Task 1: Visualization with seaborn and pandas.


Load the `solar_mesh.csv` file as a dataframe with pandas. In the file the first row and the first colum show binned coordinates. Your task is to graph a heatmap with the weights being the values withing that coordinate. (preferabily with seaborn)

As an example at the coordinate bin  (47.511, 47.601], (6.061, 6.219], the weight should be 0, but at (50.743, 50.825], (6.061, 6.219] the weight should be 7720. For bonus points you can normalize all the weights.




## Task 2: Backend development

In a completely seperate project, create a FLASK project with 3 endpoints: 
- `/api/hello` -> should return the text "hello" on a GET request
- `/api/yourdata` -> On a POST request, it should return the `data` field from the request body
- `/api/rand` -> should return a random status code between 400 and 600.
