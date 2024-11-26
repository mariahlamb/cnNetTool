# cnNetTool

[![Release Version](https://img.shields.io/github/v/release/sinspired/cnNetTool?display_name=tag&logo=github&label=Release)](https://github.com/sinspired/cnNetTool/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/sinspired/cnNetTool?logo=github)
](https://github.com/sinspired/cnNetTool)
[![GitHub last commit](https://img.shields.io/github/last-commit/sinspired/cnNetTool?logo=github&label=最后提交：)](ttps://github.com/sinspired/cnNetTool)

全面解锁Github，解决加载慢、无法访问等问题！解锁Google翻译，支持chrome网页翻译及插件，解锁划词翻译，以及依赖Google翻译API的各种平台插件。解锁tinyMediaManager影视刮削。

自动设置最佳DNS服务器。

> 适合部分地区饱受dns污染困扰，访问 GitHub 卡顿、抽风、图裂，无法使用Chrome浏览器 自带翻译功能，无法刮削影视封面等问题。分别使用 `setDNS` 自动查找最快服务器并设置，使用 `setHosts` 自动查找DNS映射主机并设置。支持Windows、Linux、MacOS。Enjoy!❤

> [!NOTE]
> 首次运行大约需要2分钟以获取DNS主机，请耐心等待。后续运行速度大约10秒左右

## 一、使用方法

### 1.1 自动操作

直接下载下方文件，解压后双击运行，enjoy❤！

[![Release Detail](https://img.shields.io/github/v/release/sinspired/cnNetTool?sort=date&display_name=release&logo=github&label=Release)](https://github.com/sinspired/cnNetTool/releases/latest)

> 强烈建议采用本方法，如果喜欢折腾，可以继续往下看。

### 1.2 手动操作

#### 1.2.1 复制下面的内容

```bash

# cnNetTool Start in 2024-11-26 20:19:57 +08:00
140.82.113.25	alive.github.com
20.205.243.168	api.github.com
140.82.112.22	central.github.com
20.205.243.165	codeload.github.com
140.82.112.22	collector.github.com
20.205.243.166	gist.github.com
20.205.243.166	github.com
140.82.112.17	github.community
146.75.29.194	github.global.ssl.fastly.net
16.15.193.242	github-com.s3.amazonaws.com
52.216.171.19	github-production-release-asset-2e65be.s3.amazonaws.com
140.82.112.25	live.github.com
13.107.42.16	pipelines.actions.githubusercontent.com
185.199.111.154	github.githubassets.com
185.199.110.153	github.io
185.199.110.153	githubstatus.com
185.199.110.153	assets-cdn.github.com
185.199.109.133	avatars.githubusercontent.com
185.199.109.133	avatars0.githubusercontent.com
185.199.109.133	avatars1.githubusercontent.com
185.199.109.133	avatars2.githubusercontent.com
185.199.109.133	avatars3.githubusercontent.com
185.199.109.133	avatars4.githubusercontent.com
185.199.109.133	avatars5.githubusercontent.com
185.199.109.133	camo.githubusercontent.com
185.199.109.133	cloud.githubusercontent.com
185.199.109.133	desktop.githubusercontent.com
185.199.109.133	favicons.githubusercontent.com
185.199.109.133	github.map.fastly.net
185.199.109.133	media.githubusercontent.com
185.199.109.133	objects.githubusercontent.com
185.199.109.133	private-user-images.githubusercontent.com
185.199.109.133	raw.githubusercontent.com
185.199.109.133	user-images.githubusercontent.com
3.167.192.104	tmdb.org
3.167.192.104	api.tmdb.org
3.167.192.104	files.tmdb.org
3.167.212.23	themoviedb.org
3.167.212.23	api.themoviedb.org
3.167.212.23	www.themoviedb.org
3.167.212.23	auth.themoviedb.org
169.150.207.213	image.tmdb.org
169.150.207.213	images.tmdb.org
52.94.225.248	imdb.com
13.35.217.192	www.imdb.com
52.94.237.74	secure.imdb.com
13.226.254.49	s.media-imdb.com
52.94.228.167	us.dd.imdb.com
13.226.254.49	www.imdb.to
52.94.228.167	imdb-webservice.amazon.com
98.82.155.134	origin-www.imdb.com
18.164.172.214	m.media-amazon.com
18.154.126.231	Images-na.ssl-images-amazon.com
18.154.126.231	images-fe.ssl-images-amazon.com
146.75.29.16	images-eu.ssl-images-amazon.com
3.162.52.224	ia.media-imdb.com
146.75.29.16	f.media-amazon.com
108.157.32.37	imdb-video.media-imdb.com
13.226.220.89	dqpnq362acqdi.cloudfront.net
142.250.189.6	translate.google.com
142.250.189.6	translate.googleapis.com
142.250.189.6	translate-pa.googleapis.com
54.230.21.57	plugins.jetbrains.com
54.230.21.57	download.jetbrains.com
54.230.21.57	cache-redirector.jetbrains.com

# Update time: 2024-11-26 20:19:57 +08:00
# GitHub仓库: https://github.com/sinspired/cnNetTool
# cnNetTool End

```

该内容会自动定时更新， 数据更新时间：2024-11-26 20:19:57 +08:00

#### 1.2.2 修改 hosts 文件

hosts 文件在每个系统的位置不一，详情如下：
- Windows 系统：`C:\Windows\System32\drivers\etc\hosts`
- Linux 系统：`/etc/hosts`
- Mac（苹果电脑）系统：`/etc/hosts`
- Android（安卓）系统：`/system/etc/hosts`
- iPhone（iOS）系统：`/etc/hosts`

修改方法，把第一步的内容复制到文本末尾：

1. Windows 使用记事本。
2. Linux、Mac 使用 Root 权限：`sudo vi /etc/hosts`。
3. iPhone、iPad 须越狱、Android 必须要 root。


## 二、安装

首先安装 python，然后在终端中运行以下命令：

```bash
git clone https://github.com/sinspired/cnNetTool.git
cd cnNetTool
pip install -r requirements.txt
```
这将安装所有依赖项

## 参数说明

**cnNetTool** 可以接受以下参数：

### DNS 服务器工具 `SetDNS.py`

* --debug 启用调试日志
* --show-availbale-list, --list 显示可用dns列表，通过 --num 控制显示数量
* --best-dns-num BEST_DNS_NUM, --num 显示最佳DNS服务器的数量
* --algorithm --mode {region,overall} 默认 `region` 平衡IPv4和ipv6 DNS
* --show-resolutions, --show 显示域名解析结果

### Hosts文件工具 `SetHosts.py`

* -log 设置日志输出等级，'DEBUG', 'INFO', 'WARNING', 'ERROR'
* -num --num-fastest 限定Hosts主机 ip 数量
* -max --max-latency 设置允许的最大延迟（毫秒）
* -v --verbose 打印运行信息

命令行键入 `-h` `help` 获取帮助

`py SetDNS.py -h`

`py SetHosts.py -h`

## 三、运行

请使用管理员权限，在项目目录运行，分别设置解析最快的DNS服务器，更新hosts文件。 **接受传递参数，大部分时候直接运行即可**。

```bash
py SetDNS.py 
py SetHosts.py
```
可执行文件也可带参数运行
```pwsh
./SetDNS.exe --best-dns-num 10
./SetHosts.exe --num-fastest 3 --max-latency 500 
```

