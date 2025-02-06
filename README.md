# Ollama Implement

這是一個 Ollama 實作練習的專案，旨在學習如何使用 Docker 和 Docker Compose 部署 Ollama 模型服務。

## 目標

本專案使用 Docker Compose 來部署 Ollama 的容器，並提供簡單的配置，幫助開發者在自己的環境中運行 Ollama 服務。

## 啟動服務

```bash
docker-compose up -d
```

## 檢查服務是否運行正常

```bash
curl http://localhost:11434
```

## 停止服務

```bash
docker-compose down
```

## 參考文章
[Ollama 在本機環境輕鬆執行 LLM 及其延伸應用](https://reurl.cc/xpbpAE)

