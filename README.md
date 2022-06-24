# 安裝方式

## docker 設定檔

```
cp docker-compose-sample.yml docker-compose.yml
```

## 啟動 docker

```
docker-compose up -d --build
```

## 安裝 vue library

```
docker exec -ti my-project-03_vite_1 yarn
```

## 執行 vue

```
docker exec -ti my-project-03_vite_1 yarn dev
```

## 網站

```
http://localhost:3000/
```