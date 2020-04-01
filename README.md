# frp docker
非常简单地把 frp docker化，目的只是为了方便使用

## 服务端用法
```bash
docker run --rm -d --name=frps -v /root/frp/frps.ini:/app/frps.ini --network host fwchen/frps-docker:latest
```
