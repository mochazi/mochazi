<!--suppress ALL -->

# 🤸 ஐ Mochazi ஐ <img alt="GitHub followers" src="https://img.shields.io/github/followers/mochazi?style=flat-square&logo=github" /> <a href="https://twitter.com/mochazi888"><img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/mochazi888?style=flat-square&logo=twitter" /></a>

<p>
<img align="right" width="40%" src="rain0.gif" />

```python
import mitmproxy.http
from mitmproxy import ctx

class Counter:

    def request(self, flow: mitmproxy.http.HTTPFlow):

        ctx.log.info(flow.request.url)
        ctx.log.warn(flow.request.url)
        ctx.log.error(flow.request.url)

    def response(self, flow: mitmproxy.http.HTTPFlow):
        
        if "https://github.com/mochazi" in flow.request.url:
            flow.response.set_text("Hi, I am Mochazi!")
        
addons = [
    Counter()
]
```

</p>

# 📕 ❀ Languages ❀

<code><img height="30" width="30" src="python.png"></code>
<code><img height="30" width="30" src="cpp.png"></code>
<code><img height="30" width="30" src="java.png"></code>
<code><img height="30" width="30" src="golang.png"></code>

# 📃 〄 Analysis 〄

<img height="160" width="47%" align="left" src="https://github-readme-stats.vercel.app/api?username=mochazi&count_private=true&show_icons=true&theme=radical" />
<img height="160" width="47%" align ="right" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mochazi&theme=radical" />
<br><br><br><br><br><br><br><br><br>
<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=mochazi&theme=monokai" />

# 📞 ❅ Contact ❅

```text
Email: mochazi888@gmail.com
Twitter: @mochazi888
Github: @mochazi
```

[![☬](https://img.shields.io/badge/-@mochazi-%23181717?style=flat-square&logo=github)](https://github.com/mochazi)
