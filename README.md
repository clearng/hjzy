# 请注意！

当你在左侧切换页面时，很有可能会出现这个页面

<figure><img src="https://cdn.staticaly.com/gh/clearng/klyme-api-img@main/65e48f615b9340d47a6b879d44921f2.njebex435tc.webp" alt=""><figcaption></figcaption></figure>

别担心，这是正常的，点击“重装”即可。

具体为什么会这样？Cloudflare的CDN一次只能返回一版内容，而Gitbook切换页面时会视为同一次会话，因此CloudflareCDN不会返回内容，就报错了。
