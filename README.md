* blockchain docker template for ctf

```
cd docker
docker build -t "easyassembly" . (注意最后的点)\
docker run -d -p "0.0.0.0:pub_port:10001" -h "easyassembly" --name="EasyAssembly" easyassembly
```

* `pub_port` 替换成你想要开放给选手的端口
