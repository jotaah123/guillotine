# Guillotine

Guillotine - HTTP Security Headers Finder



##### Finds the security headers that are not enabled in a specific domain.

![test](https://raw.githubusercontent.com/Gohanckz/Banners/master/bannerGuillotine.png)

### HTTP Security Headers List

you can detect the following HTTP security headers:

* Strict-Transport-Security
* X-XSS-Protection
* X-Content-Type-Options
* X-Frame-Options
* Content-Security-Policy
* Public-Key-Pins
* X-Permitted-Cross-Domain
* Referrer-Policy
* Expect-CT
* Feature-Policy
* Content-Security-Policy-Report-Only
* Expect-CT
* Public-Key-Pins-Report-Only
* Upgrate-Insecure-Requests
* X-Powered-By

**note:** you can add security headers by directly modifying the code.

### INSTALL

```
pip install -r requirements.txt
```

### USAGE

The use is very simple.

```
python guillotine.py -t https://www.domain.com
```

DEVELOPED| CONTACT | VERSION
----------|---------|-------
Gohanckz |gohanckz@lesand.cl | 1.0
W0lf_F4ng|ms@w0lff4ng.org| 1.0
