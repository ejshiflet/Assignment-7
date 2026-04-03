# Assignment-7

Purpose: The purpose of this project is to show trend within the iris dataset. It also uses the loan dataset to find trends by visualizing. 

Design and Implementation: The data is loaded from the iris data set. Then, a scatterplot is made that uses different colors for all the different flower species. After, a bar graph is shown to display the difference in petal length between each flower species. For the last graph, a histogram is shown of all 3 types of flowers. This allows us to see the sepal length distribution of every species. For part 2, the csv is loaded into a data frame. Then, it uses the income and loan amount to make a scatterplot. After, another scatterplot is made using the loan terms and loan amount. Both of these graphs required coverting the value to integers. The last is a bar graph that counts the number of people that rent, own, and have a mortgage.

Methods: 
pd.DataFrame(): Converts the raw Iris data into a table.
.groupby(): Groups data by a specific column
.mean(): Calculates the average value of a numerical column.
.read_csv(): Loads data from an external CSV file into a DataFrame.
.astype(str): Converts a column's data type to strings
.str.replace(): Searches for specific characters (like £ or commas) and removes or replaces them.
pd.to_numeric(): Converts strings back into numbers for plotting
.dropna(): Removes rows that contain missing values
.count(): Counts how many times a specific value appears.
plt.figure(): Creates a new blank plot
plt.scatter(): Draws a scatter plot to show the relationship between two variables using dots.
plt.bar() and .plot(kind='bar'): Creates bar graph
plt.hist(): Creates a histogram to show the distribution
plt.title(), plt.xlabel(), plt.ylabel(): Adds text labels to the top and sides of the chart
plt.legend(): Adds a key to plot
plt.xticks(rotation=0): Controls the orientation of the labels on the horizontal axis.
plt.show(): show plot on screen
plt.subplots(): A helper that creates both a figure and an axis
load_iris(): data of 3 species of flowers

Part 1 Graph Explanations:
1. The first graph that is a scatter plot gives a clear visual on the difference in species sizes. It also shows how the height relates to the width. It shows that the size in order is usually setosa, versicolor, then virginicia as the biggest. It also shows that the length is usually more than double the width.
2. The second graph that is a bar graph clearly shows the average size of each species petal length. This shows which is the trend of the last graph with virginicia being the biggest but now gives use the average of each species petal length.
3. The third graph that is an overlapped histogram shows the sepal length distribution of each species seperately. It shows how the sometimes overlapp with one another and where the general sepal length of each species lands.

Part 2 Graph Explanations:
1. The first graph shows a graph of loan amount vs income. This graph helped me understand that there is a slight relationship that shows when the customers income is higher they do not have as small of a loan. This is shown on the left side of the graph.
2. The second graph shows a scatter plot that shows term years vs loan amount. Using this graph, you can see that there is a tendacy for 10 year term loans to have a higher loan amount. There is a small amount of dots appearing on the left half of the graph for 10 year loan terms.
3. The last graph is a bar graph that shows the different types of ownership. It could be own, rent, or mortgage. This bar graph clearly displays that renting is most common with over 16000 people. Then mortgage a small amount behind. Own being the least with around 23000 people.
