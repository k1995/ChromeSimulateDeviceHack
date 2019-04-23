​        You can use **Device Mode** in **Chrome DevTools**(F12) to simulate a mobile viewport.

But it only change the `navigator.userAgent`, while `navigator.platform` remains unchanged.

This Chrome extension helps you solve this problem.



​        我们在使用Chrome F12模拟手机请求的时候，Chrome只会修改UserAgent等属性，`navigator.platform`保持不变，Windows平台下该值一般为`Win32`。

​        而国内很多网站，是根据`navigator.platform`做跳转，比如某度。该插件就是解决这个问题。