## 编译和使用
```bash
sudo apt update
sudo apt install gcc make
sudo apt install libpcre3-dev zlib1g-dev
sudo apt install libssl-dev
```

## 配置和编译
```bash
# ./auto/configure
./auto/configure --with-debug --prefix=/home/aaron/projects/nginx/build --with-cc-opt=-O0
make
```

## 安装
```bash
sudo make install

```

## 启动
```bash
# 默认
# sudo /usr/local/nginx/sbin/nginx
sudo /home/aaron/projects/nginx/build/sbin/nginx
```

## 验证
```bash
curl localhost
```

