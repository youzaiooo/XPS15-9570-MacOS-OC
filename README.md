- OpenCore0.73，只是自己的oc备份，捣鼓了一下顺便分享出来而已，三码麻烦自己生成
- 驱动啥啥的是搬的xxxzc的，感谢xxxzc大佬的分享～～～具体可以去xxxzc大佬页面查看详情https://github.com/xxxzc/xps15-9570-macos
#
| 型号   | XPS15-9570/MacBookPro15,1    | 版本   | 11.6              |
| :----- | :--------------------------- | :----- | :------------------ |
| 处理器 | Intel Core i5-8300H          | 图形   | UHD Graphics 630  |
| 内存   | 海盗船 2666 DDR4 16GB         | 硬盘   | Samsung 970evo 1tb|
| 声卡   | ***************              | 网卡   | BCM94352Z         |
| 内屏   | ******************           | 显示器 | 1080p 60hz        |
# 
#
- 另外我换了97Wh大电池
#
- Intel网卡可能不可用，博通/戴尔网卡ok，如需要Intel网卡版本请前往xxxzc大佬主页下载https://github.com/xxxzc/xps15-9570-macos
- 雷电3不能用
- 指纹不能用且无解
- (其他的我不知道会不会有啥问题。。目前用着完美)
#
- 如果你的屏幕是4k的，你需要修改以下两个配置：
- 找到 `uiscale`，修改为 `Ag==`
- 找到 `dpcd-max-link-rate`，将值修改为 `FAAAAA==`
