# tumblr-crawler
Download images from tumblr 

Main repo "https://github.com/dixudx/tumblr-crawler"

### Use sites.txt

```
vogue,gucci
vogue2, gucci2
```

### Use Proxies (Optional)
You can validate the content by visiting <http://jsonlint.com/>.
If `./proxies.json` is an empty file, no proxies will be used during downloading.
If you are using Shadowsocks with global mode, your `./proxies.json` can be,

```
{
"http": "socks5://127.0.0.1:1080",
"https": "socks5://127.0.0.1:1080" 
}
```
