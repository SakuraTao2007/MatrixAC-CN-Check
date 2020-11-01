# Matrix AntiCheat Check中文配置文件（注释汉化）。

如何使用？

在config.yml中替换如下内容：

cloud_config:
 # Enable this feature? (default: false)
 enable: true
 
 # you can add multiple links here, it can avoid losing configuration files due to a link going offline
 # If all links going offline, Matrix will use the default configuration
 links:
   - 'https://cdn.jsdelivr.net/gh/SakuraTao2007/MatrixAC-CN-Check@2.0/checks.yml'
