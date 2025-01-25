# Servidor de Live Streaming com NGINX

Servidor para live streaming

## Como executar

Suba os containers utilizando docker compose
```
docker-compose up --build
```

Abra o [OBS](https://obsproject.com/pt-br/download) > Configurações > Transmissão > Servidor
```
rtmp://localhost:1935/live
```
Clique em ok e depois clique em **Iniciar transmissão**

## Como assistir a transmissão
No chrome com a [ MPEG-DASH + HLS Playback](https://chromewebstore.google.com/detail/native-mpeg-dash-+-hls-pl/cjfbmleiaobegagekpmlhmaadepdeedn) ou no Safari acesse:
```
http://localhost:8081/live/.m3u8
```


# Live Streaming Server with NGINX

Live streaming server

## How to run

Upload the containers using docker compose
```
docker-compose up --build
```

Open [OBS](https://obsproject.com/pt-br/download) > Settings > Broadcast > Server
```
rtmp://localhost:1935/live
```
Click ok and then click **Start broadcast**

## How to watch the broadcast
In chrome with [MPEG-DASH + HLS Playback](https://chromewebstore.google.com/detail/native-mpeg-dash-+-hls-pl/cjfbmleiaobegagekpmlhmaadepdeedn) or in Safari access:
```
http://localhost:8081/live/.m3u8
```
