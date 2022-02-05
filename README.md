<h1 align="center">tumblr-crawler</h1>

This is a [Python](https://www.python.org) script that you can easily download all the photos and videos from your favorite tumblr blogs.

### Use sites.txt

```
kret, terk
cee, eec
```

### Use Proxies (Optional)
If `./proxies.json` is an empty file, no proxies will be used during downloading.

Create `./proxies.json and add

```json
{
    "http": "socks5://127.0.0.1:1080",
    "https": "socks5://127.0.0.1:1080"
}
```

> Main repo "https://github.com/dixudx/tumblr-crawler"