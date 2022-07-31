# docker-linux-tweet-app

# 🚀 Docker NGINX website that allows a user to send a tweet. 🚀

https://github.com/coding-to-music/docker-linux-tweet-app

From / By Brian Christner https://github.com/vegasbrianc

https://github.com/vegasbrianc/linux_tweet_app

## Environment variables:

```java

```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/docker-linux-tweet-app.git
git push -u origin main
```

# Linux Tweet Apps

This is very simple NGINX website that allows a user to send a tweet.

It's mostly used as a sample application for Docker 101 workshops.

To use it:

Build it:
`docker build -t linux_tweet_app .`

Run it:
`docker container run --detach -p 80:80 linux_tweet_app`
