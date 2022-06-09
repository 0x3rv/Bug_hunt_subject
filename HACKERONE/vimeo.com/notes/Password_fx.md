## update pass
- [ ] exchage cookies of pass update
- [x] max passwrord dos
- [ ] Password Policy Bypass
- [ ] 




```
POST /jserrors/1/689d5b4562?a=2011224&sa=1&v=1208.49599aa&t=Unnamed%20Transaction&rst=125247&ck=1&ref=https://vimeo.com/settings/account/password HTTP/1.1

```

## some refrence report
1. [#17160 Password Policy issue (Weak Protect) (hackerone.com)](https://hackerone.com/reports/17160)
2. [#970157 Bypass Password Authentication to Update the Password (hackerone.com)](https://hackerone.com/reports/970157)
3. [#287758 Bypass insecure password validation (hackerone.com)](https://hackerone.com/reports/287758)
4. [#770504 Bypass Password Authentication for updating email and phone number - Security Vulnerability (hackerone.com)](https://hackerone.com/reports/770504)
5. [#982293 Bypass Password Authentication to Update the Password (hackerone.com)](https://hackerone.com/reports/982293)
6. [#246042 Password Policy Issue (hackerone.com)](https://hackerone.com/reports/246042)



```
POST /settings?action=change_password HTTP/1.1
Host: vimeo.com
Cookie: vuid=pl1317212593.1817348053; language=en; OptanonConsent=isGpcEnabled=0&datestamp=Wed+Jun+08+2022+12%3A30%3A34+GMT%2B0530+(India+Standard+Time)&version=6.29.0&isIABGlobal=false&hosts=&landingPath=NotLandingPage&groups=C0001%3A1%2CC0002%3A1%2CC0003%3A1%2CC0004%3A1&AwaitingReconsent=false&geolocation=IN%3BUP; _gcl_au=1.1.1950390668.1654350668; __pdst=baf3a13b76eb461ebf27fa2d325a6b60; sd_client_id=e69a294a-a674-4918-adc2-3aeee7f600af; _scid=5c3186b5-6928-4c8e-8717-06e9448acc9c; _rdt_uuid=1654350668176.f592fe41-863c-4efc-a153-6ea897178d95; _sctr=1|1654281000000; _ga=GA1.2.603165134.1654350670; _fbp=fb.1.1654350670730.416760242; _clck=15i8w1s|1|f25|0; afUserId=288255cf-2310-4fd9-91e7-71c535db07fc-p; AF_SYNC=1654350672365; _abexps=%7B%22202%22%3A%22no%22%2C%221057%22%3A%22false%22%2C%221462%22%3A%22variant_screen%22%2C%222363%22%3A%22variant%22%7D; _cc_id=1b2c5674237db73e5fdbee0c3bb44b11; panoramaId_expiry=1654955769068; panoramaId=3f364c3b801bdb2e2223444ba6f216d53938a1648ea28542831bc8efbf9311a7; vimeo_gdpr_optin=1; OptanonAlertBoxClosed=2022-06-08T07:00:34.635Z; _ga_126VYLCXDY=GS1.1.1654351010.1.1.1654351510.51; vimeo_cart=%7B%22pro%22%3A%7B%22store%22%3A%22pro%22%2C%22version%22%3A1%2C%22quantities%22%3A%7B%221174154%22%3A1%7D%2C%22items%22%3A%5B%7B%22id%22%3A1174154%7D%5D%2C%22attributes%22%3A%5B%5D%2C%22currency%22%3A%22USD%22%2C%22items_sorted_by_index%22%3A%5B%5D%7D%2C%22stock%22%3A%7B%22store%22%3A%22stock%22%2C%22version%22%3A1%2C%22quantities%22%3A%5B%5D%2C%22items%22%3A%5B%5D%2C%22attributes%22%3A%5B%5D%2C%22currency%22%3A%22USD%22%2C%22items_sorted_by_index%22%3A%5B%5D%2C%22items_count%22%3A0%7D%7D; has_logged_in=1; __ssid=9511cc98-3a97-4819-bf50-2f305ebe367e; _gd_svisitor=edefc817ff2b0000996a9b629101000085932900; _gd_visitor=8945d826-5dd5-4e93-862a-c312ee0059db; _an_uid=5472215238642038706; drift_aid=c276d31a-3630-4265-8e46-70275e2b61c1; driftt_aid=c276d31a-3630-4265-8e46-70275e2b61c1; _abexps=%7B%22202%22%3A%22no%22%2C%221057%22%3A%22false%22%2C%221462%22%3A%22variant_screen%22%2C%222363%22%3A%22variant%22%7D; _delighted_web={%22j9SrNrucuaGn962P%22:{%22_delighted_fst%22:{%22t%22:%221654352753313%22}}%2C%22ekKsM8q7hLDyvv83%22:{%22_delighted_fst%22:{%22t%22:%221654353028149%22}}%2C%223OqDOZpD8s1OHjxk%22:{%22_delighted_fst%22:{%22t%22:%221654671111070%22}}%2C%220dqrnAdbjwmpQwv9%22:{%22_delighted_fst%22:{%22t%22:%221654671111084%22}}}; has_uploaded=1; AMCV_98CF678254E93B1B0A4C98A5%40AdobeOrg=1176715910%7CMCMID%7C32549739646301682810626772471949989778%7CMCAAMLH-1655270211%7C12%7CMCAAMB-1655270211%7C6G1ynYcLPuiQxYZrsz_pkqfLG9yMXBpb2zX5dvJdYQJzPXImdj0y%7CMCOPTOUT-1654672611s%7CNONE%7CvVersion%7C5.4.0; __cf_bm=OmWrzyb1_6WVUoxk6JexzX2v_hpP9LzX3Y7GMo2py9k-1654671082-0-AcBBoknXccs2occR1fJofr8P92+ANsz0diIizRD6O8juMayW5Wie/2omBTZ0nVa9XwqSngIB2pT/ffzQtGZWKBo=; sd_identity={"userId":"177584421","traits":{"email":"177584421","userId":"177584421","properties":{"sfmc":{"primarySubscriberKey":"177584421"}}}}; recent_gtm_event=pageURL: https://vimeo.com/ | clickText: undefined | clickURL: https://vimeo.com/user177584421; _gid=GA1.2.729005017.1654671087; vimeo=OHLZZetddDLMVHLXedXZLLL4MxHLaNPLdLeLL3tdL4%2CX3XaZLDdPae%2CcZa%2CPXcZ%2C3S3MiwiViN5_59biw_ViY3HLXedXZLLL4M5i_Ic9j3H9ubNwizNVi9wMIHdSX3eXecSZ3LtdB4%2CB334d3L%2CL%2CtcaDBteDdeZ%2CZ4Pee%2CaXZcte4Z3eecPN%2CtPX3; is_logged_in=1; _clsk=780rgh|1654671647171|3|1|www.clarity.ms/eus-f/collect; _uetsid=6885ee80e6f711ec9ca553fdbf45ef62; _uetvid=62ab0560e40d11ec85d5fd536a7b683a
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:101.0) Gecko/20100101 Firefox/101.0
Accept: */*
Accept-Language: en-US,en;q=0.5
Accept-Encoding: gzip, deflate
Referer: https://vimeo.com/settings/account/password
Content-Type: application/x-www-form-urlencoded; charset=UTF-8
X-Requested-With: XMLHttpRequest
Origin: https://vimeo.com
Content-Length: 175
Sec-Fetch-Dest: empty
Sec-Fetch-Mode: cors
Sec-Fetch-Site: same-origin
Te: trailers
Connection: close

current_password=§rYiR%23FV!c665J7w§&new_password=rYiR%23Fwww665J7w5&new_password_confirm=rYiR%23www665J7w5&token=e874a7c6525754792bb46827ff79c52504b9571e.jfovb98x80.1654671636
```