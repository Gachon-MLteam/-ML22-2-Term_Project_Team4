# [22-2] Machine Learning Term Project 
### _TEAM 4_
---
# Goals
- Recommend animation to users

# Structure & Flow
<img width="460" alt="image" src="https://user-images.githubusercontent.com/65584699/204468203-706ac91b-23bc-4e4f-83d3-8a79cd5c8653.png">

# Output
- Item-based filtering
<img width="758" alt="image" src="https://user-images.githubusercontent.com/65584699/204482949-ff4d887f-8365-4d42-8dfb-243b5a3f7877.png">

- SVD
<img width="747" alt="image" src="https://user-images.githubusercontent.com/65584699/204482996-36e367b1-4ff1-4283-b85b-7a676291fb1e.png">

- Content based
<img width="823" alt="image" src="https://user-images.githubusercontent.com/65584699/204483130-c83acfc9-489d-4c11-8af5-565f89ed2bf7.png">


# Dataset
Anime Dataset
* link : <https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database/>

# Data Preprocessing
1. Load data
2. Remove null value
3. Data Explore
4. Split into predictor / target

# Basic Functions
````python
get_pivot_tables(row, column)
get_anime_of_user(userID)
search_anime_index(recommend_list)
````

# Item-based filtering
````python
item_based_CF(user_id, n)
````
- Detail
`get_cos_sim_table`, `recommend_item_based_CF`, `get_recommend_titles`

# User-based filtering
````python
User_based(user_id, n)
````

# SVD
````python
svd_recommend_system(user_id, n)
````

- Detail
`calculate_SVD`, `get_anime_recommended`, `get_top_recommend_list`


# Content-based filtering
````python
content_based_filtering(user_id, n)
````
- Detail
`calculate_scores`, `watched_anime`

# Main 
````python
recommend_system(USER_ID, MODE, NUMBER)
````


## Requirements

This project is currently created using the following libraries.

| library | version |
| ------ | ------ |
| python | 3.10.5 |
| pandas | 1.4.4 |
| numpy | 1.23.3 |
| scikit-learn | 1.1.2 |
| selenium |  |

### Members - _TEAM 4_
- 202035513 Kim Jiwoo
- 202035525 Seo JeongDeok
- 202035528 Shin Sooin
- 202035535 Lee jiyun





 

