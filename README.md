# weixin
微信公众号研发

# 页面适配问题
pc端显示正常,firefox开发者模式下显示正常.但是通过微信公众号打开页面整体变小.
在页面前部增加如下一行即可
`<meta name="viewport" content="width=device-width, initial-scale=1,user-scalable=no">`
