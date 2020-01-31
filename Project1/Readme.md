
Project-1 Explore Weather Trends

Extracting Data- Data was extracted using the SQL command : • There are 3 tables in the spreadsheet. They are city_data, city_list and global_data. •	Whereas, we want to know the similarities and dissimilarities of the local temperature (which is New York here) and global temperature •	So, we are taking year in the city_data and global_data as a primary key to extract only the data which is needed. Displaying only the three needed columns Years, New York average temperature and global average temperature.

Python- We used Python as a visualization and analyzing tool. Google colab was used as a tool for performing visualization with python. •	Imported packages they are: numpy, pandas and matplotlib. •	They are all used for performing the calculation by using the data and for the visualization. •	Data.head(20) is for showing the first 20 rows of data.

•	Replacing the not available feature of particular row by the overall mean of the feature so the overall mean does not get affected. •	Plotting the line chart, we can see that we cannot visualize the data properly as the variation is much more. So, we cannot understand the flow properly. So, we have to smooth the line by taking the moving average this will make easy to visualize . •	We are taking rolling 10 years of time as an average to smooth out the lines and making trends more observable.

The
The Line chart is shown above tells us: •	Overall trends looks like that the temperature is increasing in all over the world. • Even the temperature is increasing in New York also. •	As you can see the positive correlation. It means that it is increasing but not linearly increasing. •	Correlation coefficient is the deciding factor. •	There is more rapid increase in global temperature comparative to the New York temperature. •	correlation coefficient of New York
