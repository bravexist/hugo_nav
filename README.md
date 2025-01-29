# hugo_nav
静态导航站

## 修改网站



github添加公钥

config配置
```
# github.com Github
Host github.com
  HostName github.com
  ProxyCommand ncat --proxy-type socks5 --proxy 127.0.0.1:7890 %h %p
  User git
  IdentityFile ~/.ssh/*.Key
```

```
git clone https://github.com/bravexist/hugo_nav.git
```

```
git add .
git commit -m "Initial commit"
git remote add origin git@github.com:bravexist/hugo_nav.git
git push -u origin main
```