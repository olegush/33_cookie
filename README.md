# Frontend for SPA

It is a frontend for single page application.

Application logic:
* user signs up with email and password
* AJAX-request goes to server
* server registers the user and gives cookies
* frontend redirects the user to car list
* frontend requests data from server


# Deploy on localhost

Example of frontend launch on Linux, Python 3:

```bash
cd static/
python3 -m http.server 9000
```

Open page [localhost:9000](http://localhost:9000) in browser.


# Project Goals

The code is written for educational purposes. Training course for web-developers - [DEVMAN.org](https://devman.org)
