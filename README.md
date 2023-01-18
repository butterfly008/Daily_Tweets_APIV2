# Daily_Tweets_APIV2

produces 4 csv files containing Main Twitter information 

file'AcademicMain' fields : 'author id', 'created_at', 'place_id', 'referenced_id', 'Retweet', 'id', 'conversation_id' ,'lang', 
     'source', 'tweet', 'username_mentioned', 'username_mentioned_id', 'urls_expanded', 'urls', 'tag
     
file AcademicUsers contains fields: 'author id','username', 'place_id', 'description', 'name', 'followers_count', 'following_count', 'verified', 'profile_image_url'
file AcademicRetweetInfo contains fields: 'conversation_id', 'referenced_id','place_id', 'text2','username_mentioned2','username_mentioned_id2', 'url2', 'urls_expanded2', 'tag2'
file AcademicPlaces contains fields: 'place_id','name_country', 'full_name_country', 'name_country', 'country_code', 'place_type'


you will then need to merge the author id from 'AcademicMain' file with the 'AcademicUsers' file (with author id), then AcademicRetweetInfo contains reference id, 
which needs to be merged with reference id with 'AcademicMain, then 'AcademicPlaces' place id needs to be merged with place id in 'AcademicPlaces'
