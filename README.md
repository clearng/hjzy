# 请注意！

### <mark style="color:red;">复制链接到浏览器查看，不要在微信看！！！</mark>

当你在左侧切换页面时，很有可能会出现这个页面

<figure><img src="https://cdn.staticaly.com/gh/clearng/klyme-api-img@main/65e48f615b9340d47a6b879d44921f2.njebex435tc.webp" alt=""><figcaption></figcaption></figure>

别担心，这是正常的，点击“重装”即可。

具体为什么会这样？Cloudflare的CDN一次只能返回一版内容，而Gitbook切换页面时会视为同一次会话，因此CloudflareCDN不会返回内容，就报错了。那为什么我科学上网后就不会出现了呢？还是Cloudflare的问题，CDN主要是加速用的，科学上网后没必要加速，就绕过CDN直接访问源服务器，源服务器是没问题的，有问题的是CDN。
