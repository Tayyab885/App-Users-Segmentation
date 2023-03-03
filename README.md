# App User Segmentation with Machine Learning using Python

- App user segmentation is the process of grouping users based on how they engage with an app. This technique can be used to find retained users, identify user segments for marketing campaigns, and solve other business problems that require identifying users with similar characteristics. In this project, we will walk through the process of app user segmentation using machine learning and Python.

### Dataset:
- We will be using a dataset that contains information about how daily active users and users who have uninstalled an app engage with the app.
- The dataset has the following features:
  1. userid: The identity number of the user
  2. Average Screen Time: The average screen time of the user on the application
  3. Average Spent on App (INR): The average amount spent by the user on the application
  4. Left Review: Did the user leave any reviews about the experience on the application? (1 if true, otherwise 0)
  5. Ratings: Ratings given by the user to the application
  6. New Password Request: The number of times the user requested a new password
  7. Last Visited Minutes: Minutes passed by when the user was last active
  8. Status: Installed if the application is installed and uninstalled if the user has deleted the application
- You can download the dataset from [here](https://statso.io/app-users-segmentation-case-study/).

### Libraries Used:
This project utilizes the following Python libraries:

- [NumPy](https://numpy.org/) - a library for numerical computations in Python.
- [Pandas](https://pandas.pydata.org/) - a library for data manipulation and analysis.
- [Seaborn](https://seaborn.pydata.org/) - a data visualization library based on Matplotlib.
- [Scikit-learn](https://scikit-learn.org/stable/) - a library for machine learning in Python.

### Analysis:
The analysis involves the following steps:
1. Importing necessary libraries and the dataset
2. Exploring the dataset by calculating the highest, lowest, and average screen time and amount spent by users
3. Creating visualizations to explore the relationship between spending capacity and screen time and ratings given by users and average screen time
4. Using the K-means clustering algorithm to segment app users into retained and lost users


### Conclusion:
- App user segmentation is an important technique that can help businesses to identify and target users with similar characteristics. In this project, we have walked through the process of app user segmentation using machine learning and Python. The K-means clustering algorithm can be used to segment app users into different groups based on their engagement with the app. By analyzing the characteristics of these groups, businesses can gain insights into the behavior of their users and optimize their marketing and product development strategies accordingly.
