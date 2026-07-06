# FontConfig
Linux下对Noto Sans CJK中文字符日化的优化尝试

# 实现原理
调整 CJK 字体的回落方式来确保中文字符渲染优先

# 安装方式
将配置文件放至 `/etc/fonts/conf.d/`
刷新字体缓存 (`fc-cache -fv`) 即可
