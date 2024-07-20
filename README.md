# Random-Api 随机文件API

**请给个star，谢谢**

## 使用链接

[https://random.cloudns.ch](https://random.cloudns.ch)

## 部署、更新和原理

  静态文件改为使用 Cloudflare Pages 部署后获得，发现用 github 的源文件链接有点点慢，其他不变

----------
- 使用cloudflare worker配合github，实现获取path与csv_path关系，从 url.csv 文件中给出的链接来实现一个随机文件

- 不仅可以放图片，还能放文本文件，视频，等等

### 自行部署
- cloudflare 新建一个worker，把 worker.js文件的代码粘贴进去，保存（可以修改为自己的链接）
- 访问即可
### 更新说明
- 只需要git修改github上文件即可，不需要修改worker.js文件
- 有时候会有点缓存，生效要等一会儿
                
