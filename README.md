<p align="center">
    <img src="https://cdn.jsdelivr.net/gh/ruicky/ruicky.github.io/2020/06/05/jd-sign/0.png">
</p>

<p align="center">
    <img alt="Version" src="https://img.shields.io/badge/release-0.0.1-blue"/>
    <a href="https://github.com/ruicky">
        <img alt="Author" src="https://img.shields.io/badge/author-ruicky-blueviolet"/>
    </a>
</p>

# 京东自动签到
功能：
1. 获取签到最新代码
2. 替换参数值
3. 签到并发送通知

详情参考文章:[京东定时签到-GitHub 实现](https://ruicky.me/2020/06/05/jd-sign/)


# 更新
开启抓包app后, Safari浏览器登录 https://bean.m.jd.com 点击签到并且出现签到日历后, 返回抓包app搜索关键字 functionId=signBean 复制请求头Cookie填入以下Key处的单引号内即可 */

要按上面方式获取Cookie，否则运行失败

输入地址 https://plogin.m.jd.com/login/login

copy(document.cookie)


