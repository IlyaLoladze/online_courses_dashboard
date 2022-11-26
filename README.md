# online_courses_dashboard
A Power BI dahsboard, which analyzes dataset from <a href="https://www.kaggle.com/datasets/thedevastator/udemy-courses-revenue-generation-and-course-anal" target="_blank">kaggle.com</a> about online courses on <a href="https://www.udemy.com/" target="_blank">udemy</a> platform: user activity, dashboard creations on a platform, analyzing courses ratings, revenues and etc. This is a general 'management' dashboard for tracking main processes of the platform, that are provided in the dataset.

## Dataset short overview

There are 4 separate .csv files, that include information about different subjects:
 - Business courses
 - Design courses
 - Music courses
 - Web development courses

After combining all files above in one csv, deleting duplications and nan values, changing data types and adding some columns (for more details: <a href="https://github.com/IlyaLoladze/online_courses_dashboard/blob/main/data_preprocessing/courses_dash_preprocessing.ipynb" target="_blank">link</a>) we got these columns in final dataset:

| Column name | Description   |
| :---:       | :---:         |
| content_duration | |
| course_id | |
| course_title | The title of the Udemy course (String) |
| is_free | |
| level | |
| num_lectures | |
| num_reviews | |
| num_subscribers | |
| popularity | |
| price | The price of the Udemy course (Float) |
| published_date | |
| published_month | |
| published_timestampt | |
| published_Year | |
| Rating | |
| revenue | |
| subject | |
| url | The URL of the Udemy course. (String) |

price	The price of the Udemy course. (Float)
num_subscribers	The number of subscribers for the Udemy course. (Integer)
num_reviews	The number of reviews for the Udemy course. (Integer)
num_lectures	The number of lectures in the Udemy course. (Integer)
level	The level of the Udemy course. (String)
Rating	The rating of the Udemy course. (Float)
content_duration	The content duration of the Udemy course. (Float)
published_timestamp	The timestamp of when the Udemy course was published. (Datetime)
subject	The subject of the Udemy course. (String)





