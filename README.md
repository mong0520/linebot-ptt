# Line 聊天機器人 for PTT Beauty 版

## 如何加入聊天機器人

### 掃描 QR Code 或點選連結
[<img src="resource/qr_code.png">](https://line.me/R/ti/p/SFXWQpzdaY)


---

## 如何開發

### 安裝

```
go get github.com/mong0520/linebot-ptt
govendor sync
```


### 本機測試

```
# 1) 啟動 MongDB
Follow the instruction in db/

# 2) 啟動 Linebot
export PORT=${PORT}
export ChannelSecret=${ChannelSecret}
export ChannelAccessToken=${ChannelAccessToken}

go run main.go

# 3) 設定 Https 轉發
ngrok http 8080

# 4) 設定 Linebot webhook

```


### 截圖

### 待辨清單:
