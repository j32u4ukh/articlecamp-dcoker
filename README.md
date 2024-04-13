# articlecamp-docker

articlecamp 前後端用開發環境

## 建置 Docker 環境

```bash
docker-compose up -d --build
```

## Windows 環境下如何找到佔用住特定 port 的程式

netstat -ano | findstr :[port]

```bash
netstat -ano | findstr :3306
```