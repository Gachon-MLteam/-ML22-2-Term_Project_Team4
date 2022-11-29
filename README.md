# [22-2] Machine Learning Term Project 
### _TEAM 4_
---
# Goals
- Recommend animation to users

# Structure & Flow
<img width="460" alt="image" src="https://user-images.githubusercontent.com/65584699/204468203-706ac91b-23bc-4e4f-83d3-8a79cd5c8653.png">

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

### Output
<img width="735" alt="image" src="https://user-images.githubusercontent.com/65584699/204481210-e5a8eb7c-ab1a-4400-a0fb-933697450746.png">


# Content-based filtering
````python
content_based_filtering(user_id, n)
````
- Detail
`calculate_scores`, `watched_anime`

### Output

![image](https://user-images.githubusercontent.com/65584699/204472016-7795b4fe-6151-499f-a6c1-e614f2538e22.png)

# Main 
````python
recommend_system(USER_ID, MODE, NUMBER)
````

<img wi



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
- 202035535 Lee Jiyun





 

