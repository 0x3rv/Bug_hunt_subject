api leaking data disclose

```
POST /api/auth HTTP/1.1
Host: vimeo.magisto.com

GET /activity/json?count=5 HTTP/1.1
Host: vimeo.com

POST /_rv/access_token HTTP/1.1
Host: vimeo.com

GET /_rv/access_token HTTP/1.1
Host: vimeo.com

GET /_rv/viewer HTTP/1.1
Host: vimeo.com

GET /blog/category/case-study HTTP/1.1
Host: vimeo.com

GET /blog/category/video-school HTTP/1.1
Host: vimeo.com

GET /channels/staffpicks HTTP/1.1
Host: vimeo.com

GET /create/ecommerce HTTP/1.1
Host: vimeo.com

GET /create/real-estate HTTP/1.1
Host: vimeo.com

GET /create/templates HTTP/1.1
Host: vimeo.com

GET /de/upload HTTP/1.1
Host: vimeo.com

GET /experts/dashboard HTTP/1.1
Host: vimeo.com

GET /features/online-video-hosting HTTP/1.1
Host: vimeo.com

GET /log_in?modal=new HTTP/1.1
Host: vimeo.com

GET /manage/717076092/social_destinations?&fetch_display_name=true HTTP/1.1
Host: vimeo.com

POST /manage/videos?action=ACTION_LOG_PERFORMANCE HTTP/1.1
Host: vimeo.com

POST /manage/videos?action=BATCH_DELETE_CLIPS HTTP/1.1
Host: vimeo.co

POST /upload/_verify HTTP/1.1
Host: vimeo.com

GET /user177584421/likes HTTP/1.1
Host: vimeo.com


```