# FFmpeg-Linux64-master

官方的api有概率访问出错，改成mac编译版，本地手动更新，push之后自动发布release

#API

## 最新FFmpeg下载链接：
https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Linux64-master@master/dist/ffmpeg-linux64-master.7z

## 某个版本的下载链接
通过下面的API接口获取历史版本号，比如 `4.3.1`，下载链接：

https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Linux64-master@4.3.1/dist/ffmpeg-linux64-master.7z

## 原网站API：
版本号（需要提取）：https://johnvansickle.com/ffmpeg/git-readme.txt

下载链接：https://johnvansickle.com/ffmpeg/builds/ffmpeg-git-amd64-static.tar.xz

## 本搬运仓库API：
版本号：https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Linux64-master@master/version

下载链接（ `/n` 分割）：https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Linux64-master@master/download_link

API接口 Json格式：https://cdn.jsdelivr.net/gh/One-Studio/FFmpeg-Linux64-master@master/api.json

| API          | 类型     | 含义                                          |
| ------------ | -------- | --------------------------------------------- |
| Version      | string   | 版本号                                        |
| VersionList  | []string | 历史版本                                      |
| ReleaseTime  | string   | 最新版本的发布时间 (格式2020-10-20T12:16:01Z) |
| Checktime    | string   | 搬运时检查的时间                              |
| DownloadLink | []string | 下载链接                                      |
| Format       | int      | 格式(1=7z, 2=zip)                             |
| ReleaseNote  | string   | 更新日志                                      |
