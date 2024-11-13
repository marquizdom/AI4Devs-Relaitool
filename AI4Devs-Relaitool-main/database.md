### DATABASE Basic Structure MVP.

//USERS
- id
- username
- email
- password
- name
- profile_image
- bio
- link
- country
- followers
- following
- reports
- blocked
- gender
- age
- admin
- toolbox
- likes_posts
- likes_comments
- created_at
- updated_at

//POSTS
- id
- user_id
- prompt
- media
- likes
- comments_prompts
- tags_aitools
- saved
- reports
- created_at
- updated_at

//COMMENTS_PROMPTS
- id
- post_id
- user_id
- likes
- comment_prompt
- tags_aitools
- created_at
- updated_at

//AITOOLS
- id
- name
- description
- website
- image
- model_economy
- youtube_video_link
- categories
- created_at
- updated_at


//NOTIFICATIONS
- id
- username_from
- username_to
- title
- message
- aitool_id
- post_id
- comment_id
- created_at
- updated_at

//NEW_AITOOLS
- id
- username_id
- name
- description
- website
- category
- model_economy
- created_at
- updated_at












