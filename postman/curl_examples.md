# Curl examples (replace placeholders before running)

## Create a scheduled photo (replace [PAGE_ID] and [PAGE_ACCESS_TOKEN], set timestamp at least a few minutes in the future)
curl -X POST "https://graph.facebook.com/v17.0/[PAGE_ID]/photos" \
  -F 'url=https://cdn.example.com/sample.jpg' \
  -F 'caption=Test scheduled post from demo' \
  -F 'published=false' \
  -F 'scheduled_publish_time=1710000000' \
  -F "access_token=[PAGE_ACCESS_TOKEN]"

## Get scheduled post
curl -X GET "https://graph.facebook.com/v17.0/[SCHEDULED_POST_ID]?access_token=[PAGE_ACCESS_TOKEN]"

## List scheduled posts for the Page
curl -X GET "https://graph.facebook.com/v17.0/[PAGE_ID]/scheduled_posts?access_token=[PAGE_ACCESS_TOKEN]"
