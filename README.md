# plot-challenge
---
In this challenge, I read two different csv files, converted them into DataFrames using pandas, merged them together, and then performed an analysis on the combined DataFrame. This analysis includes creating charts based on observed timepoints for drug regimens and for the gender distribution within the study, calculation of final tumor volumes and subsequently boxplots to see outliers of those volumes, and seeing if there is a correlation between average mouse weight and average tumor volume. 

### Citations
I used [this](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.aggregate.html) in association with [ChatGPT](https://chatgpt.com/) to figure out how the aggregate function in pandas works. 

I used [this](https://matplotlib.org/3.4.3/gallery/ticks_and_spines/ticklabels_rotation.html) to find out how to rotate the xticks on my matplotlib chart

I used [this](https://matplotlib.org/stable/gallery/pie_and_polar_charts/pie_features.html) to trouble shoot problems that were arising when trying to use pyplot to make a pie chart.

I used [this](https://www.programiz.com/python-programming/numpy/methods/tolist) in association with [ChatGPT](https://chatgpt.com/) and [Xpert Learning Assistant](https://bootcampspot.instructure.com/courses/6483/external_tools/313) to discover the ```.tolist()``` method functionality and  subsequently use it to add lists to an existing dictionary from within a loop

I used [this](https://numpy.org/devdocs/reference/generated/numpy.array.html) in association with [ChatGPT](https://chatgpt.com/) to find a solution to a typerror when calculating regress values

I used [this](https://realpython.com/numpy-scipy-pandas-correlation-python/#correlation) as a guide to figure out the correlation coefficient in the last chart