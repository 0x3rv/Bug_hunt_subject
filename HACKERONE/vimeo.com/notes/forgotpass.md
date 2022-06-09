```
POST /forgot_password HTTP/1.1
Host: vimeo.com
Cookie: __cf_bm=fZvGpKkWf_iUWhM57JM2uAjkETcPei.XqzGtvm8GnJw-1654351609-0-AeP1andMypVJF0Yy6RdD+VK/9ht+mC4CNRI+Z5n9hGsIfzV3L2Vjhkjnyoq8T7+pjoiBvYsSJO0CmGubrEbQ/JY=; vuid=pl1317212593.1817348053; language=en; OptanonConsent=isGpcEnabled=0&datestamp=Sat+Jun+04+2022+19%3A44%3A58+GMT%2B0530+(India+Standard+Time)&version=6.29.0&isIABGlobal=false&hosts=&landingPath=NotLandingPage&groups=C0001%3A1%2CC0002%3A1%2CC0003%3A1%2CC0004%3A1&AwaitingReconsent=false&geolocation=IN%3BUP; _gcl_au=1.1.1950390668.1654350668; __pdst=baf3a13b76eb461ebf27fa2d325a6b60; sd_client_id=e69a294a-a674-4918-adc2-3aeee7f600af; _scid=5c3186b5-6928-4c8e-8717-06e9448acc9c; _rdt_uuid=1654350668176.f592fe41-863c-4efc-a153-6ea897178d95; _sctr=1|1654281000000; _ga=GA1.2.603165134.1654350670; _gid=GA1.2.1511211328.1654350670; _fbp=fb.1.1654350670730.416760242; _clck=15i8w1s|1|f21|0; _clsk=hvizda|1654352101814|11|0|www.clarity.ms/eus-f/collect; afUserId=288255cf-2310-4fd9-91e7-71c535db07fc-p; AF_SYNC=1654350672365; _abexps=%7B%221462%22%3A%22variant_screen%22%2C%222363%22%3A%22variant%22%7D; _cc_id=1b2c5674237db73e5fdbee0c3bb44b11; panoramaId_expiry=1654955769068; panoramaId=3f364c3b801bdb2e2223444ba6f216d53938a1648ea28542831bc8efbf9311a7; vimeo_gdpr_optin=1; OptanonAlertBoxClosed=2022-06-04T14:14:58.447Z; _ga_126VYLCXDY=GS1.1.1654351010.1.1.1654351510.51; recent_gtm_event=pageURL: https://vimeo.com/ | clickText: Forgot your password? | clickURL: https://vimeo.com/forgot_password; sd_identity={"userId":"177584421","traits":{"email":"177584421","userId":"177584421","properties":{"sfmc":{"primarySubscriberKey":"177584421"}}}}; vimeo_cart=%5B%5D; _gat_UA-76641-8=1; _uetsid=62ab0090e40d11ec8502c57c86eead0f; _uetvid=62ab0560e40d11ec85d5fd536a7b683a
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:101.0) Gecko/20100101 Firefox/101.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Content-Type: application/x-www-form-urlencoded
Content-Length: 95
Origin: https://vimeo.com
Referer: https://vimeo.com/forgot_password
Upgrade-Insecure-Requests: 1
Sec-Fetch-Dest: document
Sec-Fetch-Mode: navigate
Sec-Fetch-Site: same-origin
Sec-Fetch-User: ?1
Te: trailers
Connection: close

email=jknot006%40gmail.com&token=ce9312074a23cb7666d178f302e937ae7c5d2ec0.p1pirez79q.1654352100
```
their is token in email exchange with other unconfirmed email.

```
GET /forgot_password?email_sent=1 HTTP/1.1
```
after sending email

token 
```
sd_identity={"userId":"177584421","traits":{"email":"177584421","userId":"177584421","properties":{"sfmc":{"primarySubscriberKey":"177584421"}}}}; vimeo_cart=%5B%5D; _gat_UA-76641-8=1; _uetsid=62ab0090e40d11ec8502c57c86eead0f; _uetvid=62ab0560e40d11ec85d5fd536a7b683a
```



email
```
GET /u/?qs=0bb20871929bd208cff3e909f8abf55d2752d53a4f92d0f7d5710e7ec7802f18714182b8b8d19ef825c8e2d0a16ed58a712a7ee84ae074cd4f4143293a3928d9 HTTP/1.1
Host: click.email.vimeo.com
Cookie: __cf_bm=fZvGpKkWf_iUWhM57JM2uAjkETcPei.XqzGtvm8GnJw-1654351609-0-AeP1andMypVJF0Yy6RdD+VK/9ht+mC4CNRI+Z5n9hGsIfzV3L2Vjhkjnyoq8T7+pjoiBvYsSJO0CmGubrEbQ/JY=; vuid=pl1317212593.1817348053; language=en; OptanonConsent=isGpcEnabled=0&datestamp=Sat+Jun+04+2022+19%3A36%3A48+GMT%2B0530+(India+Standard+Time)&version=6.29.0&isIABGlobal=false&hosts=&landingPath=NotLandingPage&groups=C0001%3A1%2CC0002%3A1%2CC0003%3A1%2CC0004%3A1&AwaitingReconsent=false&geolocation=IN%3BUP; _gcl_au=1.1.1950390668.1654350668; sd_client_id=e69a294a-a674-4918-adc2-3aeee7f600af; _scid=5c3186b5-6928-4c8e-8717-06e9448acc9c; _rdt_uuid=1654350668176.f592fe41-863c-4efc-a153-6ea897178d95; _sctr=1|1654281000000; _ga=GA1.2.603165134.1654350670; _gid=GA1.2.1511211328.1654350670; _fbp=fb.1.1654350670730.416760242; _clck=15i8w1s|1|f21|0; _clsk=hvizda|1654351987195|10|0|www.clarity.ms/eus-f/collect; afUserId=288255cf-2310-4fd9-91e7-71c535db07fc-p; AF_SYNC=1654350672365; _cc_id=1b2c5674237db73e5fdbee0c3bb44b11; panoramaId_expiry=1654955769068; panoramaId=3f364c3b801bdb2e2223444ba6f216d53938a1648ea28542831bc8efbf9311a7; vimeo_gdpr_optin=1; OptanonAlertBoxClosed=2022-06-04T14:06:48.326Z; _ga_126VYLCXDY=GS1.1.1654351010.1.1.1654351510.51; recent_gtm_event=pageURL: https://vimeo.com/ | clickText: Forgot your password? | clickURL: https://vimeo.com/forgot_password; sd_identity={"userId":"177584421","traits":{"email":"177584421","userId":"177584421","properties":{"sfmc":{"primarySubscriberKey":"177584421"}}}}; vimeo_cart=%5B%5D; _uetsid=62ab0090e40d11ec8502c57c86eead0f; _uetvid=62ab0560e40d11ec85d5fd536a7b683a
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:101.0) Gecko/20100101 Firefox/101.0
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,*/*;q=0.8
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Upgrade-Insecure-Requests: 1
Sec-Fetch-Dest: document
Sec-Fetch-Mode: navigate
Sec-Fetch-Site: none
Sec-Fetch-User: ?1
Te: trailers
Connection: close


```


---
**what to try**
- [ ] exchange cookies of forgotpass with to diffrent account





```


```