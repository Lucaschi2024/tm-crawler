# 基于 Selenium 和 Tkinter 的爬取淘宝商品的Web自动化工具

## 使用指南
### 安装依赖
1. 确保已经正确安装Python
2. 安装requirements.txt中的依赖

### 安装WebDriver驱动
注意需要使用与您浏览器安装版本相对应的WebDriver，
本工具代码为Google Chrome提供适配：
[Google Chrome WebDriver](https://chromedriver.storage.googleapis.com/index.html)
115以上版本请到这里下载：[the Chrome for Testing availability dashboard](https://googlechromelabs.github.io/chrome-for-testing/)


[Selenium-Install Drivers指引](https://www.selenium.dev/documentation/webdriver/getting_started/install_drivers/)  

### 修改settings.ini

格式：
>
    <所需关键词>
    <起始页码>
    <终止页码>
    <Chromedriver path>

例如
> 
    电视
    1
    10
    /path/to/chromedriver

## 启动
>
    python ./taobaoCrawler.py
