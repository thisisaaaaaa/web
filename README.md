* you can update the web page by following the followings 
```bash
git add .
git commit -m "更新说明"
git push origin main  # 推送源码到 main 分支（备份）

hexo clean     # 清除旧缓存
hexo generate  # 生成静态文件到 public 目录
hexo deploy    # 将 public 目录推送到 GitHub Pages 分支
```