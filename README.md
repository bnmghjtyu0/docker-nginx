### start

```suggestion
docker-compose up 執行

docker-compose ps 看狀態
docker-compose down `remove container`
```

### open url:

- http://localhost:8001 docker
- http://192.168.99.100:8001/ docker-toolbox

### Reference

https://steveholgado.com/nginx-for-nextjs/#dockerising-nextjs

### 底下非相關 0.0

要上傳 nextjs-blog、nextjs-blog2 要刪掉資料夾內的 .git

```
git rm -r --cached nextjs-blog
git rm -r --cached nextjs-blog2
```

關於 git 檔名大小寫

```
git config --local core.ignorecase false
```