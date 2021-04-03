# MediaPipe
* MediaPipeのプログラム

## リポジトリ構成
```
.
├── README.md                 READMEファイル
├── .dockerignore        
├── Dockerfile                Dockerファイル
├── docker-compose.yml
└── notebook                  jupyter notebook
     └── movie                movieファイル
```

## 環境構築

* Dockderfileがあるホスト側のフォルダへ移動（例：Desktop/MediaPipe）
```
cd Desktop/MediaPipe
```

* Dockerによる環境構築（フォルダをマウント：Desktop/MediaPipe）
```
docker-compose up --build
```

* ブラウザーを立ち上げてlocalhost:8888へアクセス
* ローカルフォルダがマウントされている

## jupyter notebook説明
* GMediaPipe_movie.ipynb : MediaPipeのnotebook

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
