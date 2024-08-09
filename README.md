# SF轻小说自动签到
SF轻小说自动签到+做任务

## 配置
自行抓包SF轻小说app，把CheckIn.py里的`headers`和`read_headers`填完整(别把两个headers里的`sfsecurity`漏掉了！)



## 如何抓取session_APP和.SFCommunity
菠萝包新版具有较强的爱加密企业版，如果没有ROOT权限及frida，xposed等框架使用能力，抓取cookie的过程可能会遇到困难
1.使用frida，屏蔽检测后抓包
2.使用r0capture，注入后抓包
3.从data/data/com.sfacg/files/boluobao/log 里面，文本搜索session_APP关键词得出


MIT License
