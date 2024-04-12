# articlecamp-docker

articlecamp 前後端用開發環境

## Usage

### 反映 docker-compose.yml 的更新

```bash
docker-compose up -d
```

### 反映  Dockerfile 的更新

```bash
docker-compose up -d --build
```

### 重建環境

```bash
docker-compose down
docker-compose build --no-cache
docker-compose up -d
```

### 進入容器的終端機，以 app 為例，app 的部分填入容器名稱

```bash
docker-compose exec app bash
```

### Windows 環境下如何找到佔用住特定 port 的程式

netstat -ano | findstr 0.0:443

```bash
netstat -ano | findstr :3306
```