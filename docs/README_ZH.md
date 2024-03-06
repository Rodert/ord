[toc]

## 启动

- 编辑器启动

```bash
run --package ord --bin ord -- --commit-height-interval=0 --enable-index-brc20 --first-brc20-height=779832 --first-inscription-height=779832 --data-dir=/Volumes/HIKSEMI/ord/data11 --rpc-url=192.168.2.16:8166 --log-level=trace server
```

- 服务器启动

```bash
./ord --commit-height-interval=0 --enable-index-brc20 --first-brc20-height=779832 --first-inscription-height=779832 --data-dir=/home/s/apps/ord/data --rpc-url=127.0.0.1:8166 --bitcoin-rpc-user=username --bitcoin-rpc-pass=password --log-level=trace --log-dir=/home/s/apps/ord/data/logs
```

## 接口说明

