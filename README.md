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
