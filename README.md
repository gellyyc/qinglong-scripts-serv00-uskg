# qinglong-scripts-serv00-uskg
青龙面板脚本
# 青龙面板签到脚本

这是一个用于青龙面板的签到脚本，可以自动签到 serv00.com 和 us.kg。

## 使用方法

1.  在青龙面板中安装 `requests` 库。
2.  配置环境变量：
    *   `SERV00_COOKIE_1`
    *   `SERV00_COOKIE_2`
    *   ...
    *   `USKG_COOKIE_1`
    *   `USKG_COOKIE_2`
    *   ...
3.  将 `main.py` 文件添加到青龙面板的定时任务中，设置定时规则为 `0 8 * * *`。

## 依赖

*   requests

## 注意事项

*   请务必先分析签到API，并替换脚本中的占位符信息。
*   请确保所有的 Cookie 都是有效的。
*   请保护好你的账号信息，防止泄露。
*   请谨慎使用脚本，并自行承担风险。

## 作者

你的 GitHub 用户名

## 许可证

MIT License
