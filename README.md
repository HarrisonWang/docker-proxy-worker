# 使用说明

## 开发

```bash
# 进入工程目录
$ cd docker-proxy-worker

# 安装依赖包
$ npm i

# 本地运行
$ npm run dev
```

## 部署

1. 修改代理 Docker 镜像仓库的域名 `PROXY_REGISTRY`

2. 使用 `npm run deploy` 命令部署到 Cloudflare Workers

3. Worker 绑定自定义域名，等待 TLS 证书生效

4. 访问自定义域名
