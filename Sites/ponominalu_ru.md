# Ponominalu.ru

1. https://ponominalu.ru/
2. Current datetime: 20.06.2016 3:22 Msk
3. Browsed URLs:
    https://ponominalu.ru/
4. Research:
```
    IP:
        188.40.108.84
        WHOIS:
            inetnum:        188.40.108.64 - 188.40.108.127
            netname:        HETZNER-RZ10
            descr:          Hetzner Online AG
            descr:          Datacenter 10
            country:        DE
            admin-c:        HOAC1-RIPE
            tech-c:         HOAC1-RIPE
            status:         ASSIGNED PA
            mnt-by:         HOS-GUN
            mnt-lower:      HOS-GUN
            mnt-routes:     HOS-GUN
            created:        2010-08-13T08:35:48Z
            last-modified:  2010-08-13T08:35:48Z
            source:         RIPE
    HTTPS:
        Algo: SHA1
        Issuer:
            E = ppetryakov@luxoft.com
            CN = msk-cpsg-1.luxoft.com
            OU = IT
            O = Luxoft Professional LLC
            L = Moscow
            S = Moscow
            C = RU
        Valid to: 16 апреля 2017г. 9:28:42
        Subject: 
            CN = *.ponominalu.ru
            OU = Domain Control Validated
        
    WEB:
        Server response:
        HTTP/1.1 200 OK
        Server: nginx
        Date: Mon, 20 Jun 2016 12:40:16 GMT
        Content-Type: text/html; charset=utf-8
        Transfer-Encoding: chunked
        Connection: keep-alive
        Keep-Alive: timeout=20
        Vary: Accept-Encoding
        Set-Cookie: user_session=2d63db0decfe29589fe44446b91afe9cac0b7470; Expires=Fri, 24 Jun 2016 12:40:04 GMT; Path=/
        Set-Cookie: pn_w_u_s=%222d63db0decfe29589fe44446b91afe9cac0b7470%22; Expires=Fri, 24 Jun 2016 12:40:04 GMT; Path=/
        FarmServer: 3
        Content-Encoding: gzip
        Cache-Control: no-cache
    Static path:
        /public/css/build/
        /media/slides/
```
5. Errors
    https://ponominalu.ru/category/[]
        generates error page: Oops, an error occured This exception has been logged with id 70f0a13gl.
    https://ponominalu.ru/category/s
        generates 404 page
    http://ponominalu.ru/public/css/build/
        infinite redirects
    https://ponominalu.ru/category/%60
        generates error page "oops"
    https://ponominalu.ru/category/%3C%3E
        generates error page "oops"
    https://ponominalu.ru/search?q=&search_city=&category_id=[]&venue_id=&min_date=&max_date=&min_price=&max_price=&metro_ids=21
        empty page
    https://ponominalu.ru/search?q=&search_city=&category_id=&venue_id=&min_date=&max_date=&min_price=&max_price=&metro_ids=%27
        generates page 500 "unhandled exception"
    
6. Results