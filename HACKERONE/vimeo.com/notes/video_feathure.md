- [ ] access private video form authorization tooken
```
PATCH /videos/717211759 HTTP/1.1
Host: api.vimeo.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:101.0) Gecko/20100101 Firefox/101.0
Accept: application/vnd.vimeo.*;version=3.4.1
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Referer: https://vimeo.com/
Content-Type: application/json
Authorization: jwt eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJleHAiOjE2NTQ0MTc4NjAsInVzZXJfaWQiOjE3NzU4NDQyMSwiYXBwX2lkIjo1ODQ3OSwic2NvcGVzIjoicHVibGljIGludGVyYWN0IHByaXZhdGUgdXBsb2FkIGNyZWF0ZSBlZGl0IGRlbGV0ZSBlbWFpbCBzdGF0cyIsInRlYW1fdXNlcl9pZCI6bnVsbH0.-DTjcU6qFEc5vgi76Mhn5rRrmTXsbZkdHEX556gU1-0
Origin: https://vimeo.com
Content-Length: 147
Sec-Fetch-Dest: empty
Sec-Fetch-Mode: cors
Sec-Fetch-Site: same-site
Te: trailers
Connection: close

{"name":"file (1).mp4","description":"","privacy":{"view":"anybody","embed":"public","comments":"anybody","add":true},"content_rating":["unrated"]}
```

**decode token and change user while uploading video**

**case:** uploade same video from tow diffrent account and change user in auth tooken 

---
- [ ] payload inside video
- [ ]  encode exi data in video.
- [ ] comment and change id or cok
- [ ] deleie commrnt/video change id or cok