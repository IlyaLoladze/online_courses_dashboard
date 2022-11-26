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
| course_id | The id of the Udemy course (Int) |
| course_title | The title of the Udemy course (String) |
| is_free | The type of Udemy courses: free / paid (String) |
| level | The level of the Udemy course. (String) |
| num_lectures | The number of lectures in the Udemy course. (Integer) |
| num_reviews | The number of reviews for the Udemy course. (Integer) |
| num_subscribers | The number of subscribers for the Udemy course. (Integer) |
| popularity | A popularity of the course, that was calculated by subscribers amount (String) |
| price | The price of the Udemy course (Float) |
| published_date | Trunced to day 'published_timestampt' (Datetime) |
| published_month | Trunced to the start of the month 'published_timestampt' (Datetime) |
| published_timestampt | The timestamp of when the Udemy course was published. (Datetime) |
| published_Year | Trunced to the start of the year 'published_timestampt' (Datetime) |
| Rating | The rating of the Udemy course. (Float) |
| revenue | = num_subscribers * price |
| subject | The subject of the Udemy course. (String) |
| content_duration | The content duration of the Udemy course. (Float) |
| url | The URL of the Udemy course. (String) |

## Dashboard Pages

### Course Creations
![](https://github.com/IlyaLoladze/online_courses_dashboard/blob/main/dashboard/Page%20Course%20Creations.png)

### User Activity
![](https://github.com/IlyaLoladze/online_courses_dashboard/blob/main/dashboard/Page%20User%20Activity.png)

### Payments
![](https://github.com/IlyaLoladze/online_courses_dashboard/blob/main/dashboard/Page%20Payments.png)

### Quality Control
![](https://github.com/IlyaLoladze/online_courses_dashboard/blob/main/dashboard/Page%20Quality%20Control.png)


