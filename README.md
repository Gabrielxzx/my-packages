# 使用方法（自用packages 请勿Fork）


添加 src-git my-packages https://github.com/Gabrielxzx/my-packages 到 OpenWRT源码根目录feeds.conf.default文件

然后执行

```bash
./scripts/feeds clean
./scripts/feeds update -a
./scripts/feeds install -a
```
