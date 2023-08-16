<div align=center>

# [typecho](https://github.com/typecho/typecho)[-](https://typecho.org)[replit](https://replit.com)
</div>

**PHP (PDO SQLite)**

```bash
git clone https://github.com/gopcn/typecho-replit.git &&
shopt -s dotglob &&
mv -b typecho-replit/* ./ &&
rm -rf *~ typecho-replit .git .github database.sqlite README.md &&
echo "部署成功，点击Run使用。"
```

```bash
rm -rf admin var index.php install.php &&
git clone https://github.com/gopcn/typecho-replit.git &&
shopt -s dotglob &&
mv typecho-replit/{admin,var,index.php,install.php} ./ &&
rm -rf *~ typecho-replit .git &&
echo "操作已完成！"
```
