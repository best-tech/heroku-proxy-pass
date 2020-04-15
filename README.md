# heroku proxy pass

1. log in to heroku

2. [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/best-tech/heroku-proxy-pass)

or

```
git clone https://github.com/best-tech/heroku-proxy-pass.git
cd heroku-proxy-pass
heroku create
heroku buildpacks:add heroku-community/nginx
heroku config:set PROXY_PASS="https://aviasales.ru/?marker=18479"
git push heroku master
```