# MediaPipe
* MediaPipeのプログラム

## リポジトリ構成
```
.
├── Dockerfile
├── README.md
├── data
│   ├── Mediapipe_Face_Detection
│   │   ├── brooke-cagle-ezgW6z6oIvA-unsplash.jpeg
│   │   ├── garrett-jackson-auTAb39ImXg-unsplash.jpeg
│   │   ├── radu-florin-JyVcAIUAcPM-unsplash.jpeg
│   │   └── tracey-hocking-_veZpXKU71c-unsplash.jpeg
│   ├── mediapipe_face_mesh
│   │   ├── garrett-jackson-auTAb39ImXg-unsplash.jpeg
│   │   └── radu-florin-JyVcAIUAcPM-unsplash.jpeg
│   ├── mediapipe_hands
│   │   ├── brooke-cagle-mt2fyrdXxzk-unsplash.jpeg
│   │   └── kira-auf-der-heide-QyCH5jwrD_A-unsplash.jpeg
│   ├── mediapipe_holistic
│   │   ├── david-hofmann-e_rhazQLaSs-unsplash.jpeg
│   │   └── thao-le-hoang-v4zceVZ5HK8-unsplash.jpeg
│   ├── mediapipe_objectron
│   │   ├── aisfaris-jr-8dukMg99Hd8-unsplash.jpeg
│   │   ├── andres-jasso-PqbL_mxmaUE-unsplash.jpeg
│   │   ├── hanson-lu-XzL8YAWdirE-unsplash.jpeg
│   │   ├── s-o-c-i-a-l-c-u-t-7T8vSHYXq4U-unsplash.jpeg
│   │   └── vlad-ursache-WJ7gZ3cilBA-unsplash.jpeg
│   └── mediapipe_pose
│       ├── david-hofmann-e_rhazQLaSs-unsplash.jpeg
│       └── thao-le-hoang-v4zceVZ5HK8-unsplash.jpeg
├── docker-compose.yml
├── docs
├── models
├── notebooks
│   ├── MediaPipe_movie.ipynb
│   ├── Mediapipe_Face_Detection.ipynb
│   ├── mediapipe_face_mesh.ipynb
│   ├── mediapipe_hands.ipynb
│   ├── mediapipe_holistic.ipynb
│   ├── mediapipe_objectron.ipynb
│   ├── mediapipe_pose.ipynb
│   └── movie
│       └── sample_movie.mp4
├── setup.cfg
├── src
│   └── __init__.py
├── tests
│   └── __init__.py
└── work
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

## Display notebooks

- [View Jupyter notebooks in nbviewer](https://nbviewer.jupyter.org/github/ykato27/MediaPipe/tree/main/notebooks/)

## 動作環境
マシンスペック（Mac)
- MacBook Air (Retina, 13-inch, 2018)
- 1.6 GHz デュアルコアIntel Core i5
- 8 GB 2133 MHz LPDDR3
